<template>
  <div>
    <div class="order-body__title">Ваш заказ</div>

    <div v-if="loading">
      <q-circular-progress
        indeterminate
        rounded
        size="50px"
        color="lime"
        class="q-ma-md"
      />
    </div>

    <CartItem
      v-for="product in CART_PRODUCTS.values"
      :key="product.id"
      :product="product"
      @productPrice="productPrice"
    />
    <CartForm />
    <div class="registration-body__result">
      <div class="registration-body__total">
        Итого: <span> {{ TOTALSUM }} ₽</span>
      </div>
    </div>
  </div>
</template>

<script>
import CartForm from "../components/v-cart-form.vue";
import CartItem from "../components/v-cart-item.vue";
import { reactive, computed, ref, watch } from "vue";
import { useStore } from "vuex";

export default {
  components: {
    CartForm,
    CartItem,
  },

  setup() {
    const store = useStore();
    store.dispatch("GET_CART_PRODUCTS");

    const CART_PRODUCTS = reactive([]);
    CART_PRODUCTS.values = computed(() => store.getters.CART_PRODUCTS);

    // const quantityProductsCart = computed(
    //   () => store.getters.QUANTITY_PRODUCTS_CART
    // );

    const loading = computed(() => store.getters.LOADING_CART);

    // const TOTALSUM = ref(
    //   CART_PRODUCTS.values.reduce((a, b) => a + b.todayprice, 0)
    // );

    const TOTALSUM = ref();
    TOTALSUM.value = CART_PRODUCTS.values.reduce((a, b) => a + b.todayprice, 0);

    // watch(CART_PRODUCTS, () => {
    //   console.log("hello");
    //   TOTALSUM.value = CART_PRODUCTS.values.reduce(
    //     (a, b) => a + b.todayprice,
    //     0
    //   );
    // });

    watch(loading, () => {
      TOTALSUM.value = CART_PRODUCTS.values.reduce(
        (a, b) => a + b.todayprice,
        0
      );
    });

    const productPrice = (price) => {
      TOTALSUM.value += price;
    };

    return {
      loading,
      CART_PRODUCTS,
      productPrice,
      TOTALSUM,
    };
  },
};
</script>

<style lang="scss">
.order-body {
  &__title {
    font-family: Roboto-Black;
    font-size: 36px;
    line-height: 22px;
    font-weight: 900;
    text-transform: uppercase;
    color: #1ab9ce;
    margin: 0 0 31px 0;
    @media (max-width: 600px) {
      font-size: 30px;
    }
  }
}
.registration-body {
  &__result {
    text-align: end;
  }

  &__total {
    font-family: "Roboto-Black";
    font-size: 24px;
    line-height: 16px;
    margin: 0 0 28px 0;
    text-transform: uppercase;
    color: #333333;
    @media (max-width: 1200px) {
      font-size: 18px;
    }
    @media (max-width: 500px) {
      margin: 0 0 15px 0;
      font-size: 15px;
    }
    span {
      font-family: "Roboto-Black";
      font-size: 36px;
      line-height: 24px;
      color: #f68038;
      @media (max-width: 1200px) {
        font-size: 26px;
      }
      @media (max-width: 500px) {
        font-size: 21px;
      }
    }
  }
}
</style>
