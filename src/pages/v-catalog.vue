<template>
  <div class="">
    <q-carousel
      v-model="slide"
      transition-prev="slide-right"
      transition-next="slide-left"
      animated
      control-color="primary"
      navigation
      padding
      infinite
      arrows
      height="100%"
      class="bg-grey-1 shadow-2 rounded-borders"
    >
      <q-carousel-slide :name="1">
        <div class="wrap">
          <div class="proudcts-slider-page__item">
            <div class="proudcts-slider-page__wrapper">
              <div class="proudcts-slider-page__product product">
                <a href="#" class="product__img">
                  <img src="../assets/Catalog/imgItem.webp" alt="not found" />
                </a>
                <div class="product__title">
                  <p>
                    <a href="#"
                      >BH Fitness F1 G6414V <span>Беговая дорожка</span></a
                    >
                  </p>
                </div>
                <div class="product__footer">
                  <div class="product__oldprice">64 990</div>
                  <div class="product__buy">
                    <a href="#" class="product__cart">
                      <div></div>
                    </a>
                    <div class="product__todayprice">64 990</div>
                  </div>
                </div>
              </div>
              <div class="proudcts-slider-page__product-hover hover-product">
                <div class="hover-product__title">
                  BH Fitness F1 G6414V
                  <p>Беговая дорожка</p>
                </div>
                <div class="hover-product__options">
                  <div class="hover-product__option">
                    Тип беговой дорожки:
                    <p>Электрическая</p>
                  </div>
                  <div class="hover-product__option">
                    Скорость движения (км/ч):
                    <p>22</p>
                  </div>
                  <div class="hover-product__option">
                    Складывание:
                    <p>Есть</p>
                  </div>
                </div>
                <a href="#" class="hover-product__cart">
                  <div></div>
                </a>
                <div class="hover-product__footer">
                  <div class="hover-product__oldprice"><span>64 990</span></div>
                  <div class="hover-product__price">
                    <div class="hover-product__button">в наличии</div>
                    <div class="hover-product__todayprice">64 990</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="proudcts-slider-page__item">
            <div class="proudcts-slider-page__wrapper">
              <div class="proudcts-slider-page__product product">
                <a href="#" class="product__img">
                  <img src="../assets/Catalog/imgItem.webp" alt="not found" />
                </a>
                <div class="product__title">
                  <p>
                    <a href="#"
                      >BH Fitness F1 G6414V <span>Беговая дорожка</span></a
                    >
                  </p>
                </div>
                <div class="product__footer">
                  <div class="product__oldprice">64 990</div>
                  <div class="product__buy">
                    <a href="#" class="product__cart">
                      <div></div>
                    </a>
                    <div class="product__todayprice">64 990</div>
                  </div>
                </div>
              </div>
              <div class="proudcts-slider-page__product-hover hover-product">
                <div class="hover-product__title">
                  BH Fitness F1 G6414V
                  <p>Беговая дорожка</p>
                </div>
                <div class="hover-product__options">
                  <div class="hover-product__option">
                    Тип беговой дорожки:
                    <p>Электрическая</p>
                  </div>
                  <div class="hover-product__option">
                    Скорость движения (км/ч):
                    <p>22</p>
                  </div>
                  <div class="hover-product__option">
                    Складывание:
                    <p>Есть</p>
                  </div>
                </div>
                <a href="#" class="hover-product__cart">
                  <div></div>
                </a>
                <div class="hover-product__footer">
                  <div class="hover-product__oldprice"><span>64 990</span></div>
                  <div class="hover-product__price">
                    <div class="hover-product__button">в наличии</div>
                    <div class="hover-product__todayprice">64 990</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </q-carousel-slide>
      <q-carousel-slide :name="2" class="column no-wrap">
        <div class="wrap">
          <div class="proudcts-slider-page__item">
            <div class="proudcts-slider-page__wrapper">
              <div class="proudcts-slider-page__product product">
                <a href="#" class="product__img">
                  <img src="../assets/Catalog/imgItem.webp" alt="not found" />
                </a>
                <div class="product__title">
                  <p>
                    <a href="#"
                      >BH Fitness F1 G6414V <span>Беговая дорожка</span></a
                    >
                  </p>
                </div>
                <div class="product__footer">
                  <div class="product__oldprice">64 990</div>
                  <div class="product__buy">
                    <a href="#" class="product__cart">
                      <div></div>
                    </a>
                    <div class="product__todayprice">64 990</div>
                  </div>
                </div>
              </div>
              <div class="proudcts-slider-page__product-hover hover-product">
                <div class="hover-product__title">
                  BH Fitness F1 G6414V
                  <p>Беговая дорожка</p>
                </div>
                <div class="hover-product__options">
                  <div class="hover-product__option">
                    Тип беговой дорожки:
                    <p>Электрическая</p>
                  </div>
                  <div class="hover-product__option">
                    Скорость движения (км/ч):
                    <p>22</p>
                  </div>
                  <div class="hover-product__option">
                    Складывание:
                    <p>Есть</p>
                  </div>
                </div>
                <a href="#" class="hover-product__cart">
                  <div></div>
                </a>
                <div class="hover-product__footer">
                  <div class="hover-product__oldprice"><span>64 990</span></div>
                  <div class="hover-product__price">
                    <div class="hover-product__button">в наличии</div>
                    <div class="hover-product__todayprice">64 990</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="proudcts-slider-page__item">
            <div class="proudcts-slider-page__wrapper">
              <div class="proudcts-slider-page__product product">
                <a href="#" class="product__img">
                  <img src="../assets/Catalog/imgItem.webp" alt="not found" />
                </a>
                <div class="product__title">
                  <p>
                    <a href="#"
                      >BH Fitness F1 G6414V <span>Беговая дорожка</span></a
                    >
                  </p>
                </div>
                <div class="product__footer">
                  <div class="product__oldprice">64 990</div>
                  <div class="product__buy">
                    <a href="#" class="product__cart">
                      <div></div>
                    </a>
                    <div class="product__todayprice">64 990</div>
                  </div>
                </div>
              </div>
              <div class="proudcts-slider-page__product-hover hover-product">
                <div class="hover-product__title">
                  BH Fitness F1 G6414V
                  <p>Беговая дорожка</p>
                </div>
                <div class="hover-product__options">
                  <div class="hover-product__option">
                    Тип беговой дорожки:
                    <p>Электрическая</p>
                  </div>
                  <div class="hover-product__option">
                    Скорость движения (км/ч):
                    <p>22</p>
                  </div>
                  <div class="hover-product__option">
                    Складывание:
                    <p>Есть</p>
                  </div>
                </div>
                <a href="#" class="hover-product__cart">
                  <div></div>
                </a>
                <div class="hover-product__footer">
                  <div class="hover-product__oldprice"><span>64 990</span></div>
                  <div class="hover-product__price">
                    <div class="hover-product__button">в наличии</div>
                    <div class="hover-product__todayprice">64 990</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </q-carousel-slide>
      <q-carousel-slide :name="3" class="column no-wrap">
        <div class="wrap">
          <div class="proudcts-slider-page__item">
            <div class="proudcts-slider-page__wrapper">
              <div class="proudcts-slider-page__product product">
                <a href="#" class="product__img">
                  <img src="../assets/Catalog/imgItem.webp" alt="not found" />
                </a>
                <div class="product__title">
                  <p>
                    <a href="#"
                      >BH Fitness F1 G6414V <span>Беговая дорожка</span></a
                    >
                  </p>
                </div>
                <div class="product__footer">
                  <div class="product__oldprice">64 990</div>
                  <div class="product__buy">
                    <a href="#" class="product__cart">
                      <div></div>
                    </a>
                    <div class="product__todayprice">64 990</div>
                  </div>
                </div>
              </div>
              <div class="proudcts-slider-page__product-hover hover-product">
                <div class="hover-product__title">
                  BH Fitness F1 G6414V
                  <p>Беговая дорожка</p>
                </div>
                <div class="hover-product__options">
                  <div class="hover-product__option">
                    Тип беговой дорожки:
                    <p>Электрическая</p>
                  </div>
                  <div class="hover-product__option">
                    Скорость движения (км/ч):
                    <p>22</p>
                  </div>
                  <div class="hover-product__option">
                    Складывание:
                    <p>Есть</p>
                  </div>
                </div>
                <a href="#" class="hover-product__cart">
                  <div></div>
                </a>
                <div class="hover-product__footer">
                  <div class="hover-product__oldprice"><span>64 990</span></div>
                  <div class="hover-product__price">
                    <div class="hover-product__button">в наличии</div>
                    <div class="hover-product__todayprice">64 990</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="proudcts-slider-page__item">
            <div class="proudcts-slider-page__wrapper">
              <div class="proudcts-slider-page__product product">
                <a href="#" class="product__img">
                  <img src="../assets/Catalog/imgItem.webp" alt="not found" />
                </a>
                <div class="product__title">
                  <p>
                    <a href="#"
                      >BH Fitness F1 G6414V <span>Беговая дорожка</span></a
                    >
                  </p>
                </div>
                <div class="product__footer">
                  <div class="product__oldprice">64 990</div>
                  <div class="product__buy">
                    <a href="#" class="product__cart">
                      <div></div>
                    </a>
                    <div class="product__todayprice">64 990</div>
                  </div>
                </div>
              </div>
              <div class="proudcts-slider-page__product-hover hover-product">
                <div class="hover-product__title">
                  BH Fitness F1 G6414V
                  <p>Беговая дорожка</p>
                </div>
                <div class="hover-product__options">
                  <div class="hover-product__option">
                    Тип беговой дорожки:
                    <p>Электрическая</p>
                  </div>
                  <div class="hover-product__option">
                    Скорость движения (км/ч):
                    <p>22</p>
                  </div>
                  <div class="hover-product__option">
                    Складывание:
                    <p>Есть</p>
                  </div>
                </div>
                <a href="#" class="hover-product__cart">
                  <div></div>
                </a>
                <div class="hover-product__footer">
                  <div class="hover-product__oldprice"><span>64 990</span></div>
                  <div class="hover-product__price">
                    <div class="hover-product__button">в наличии</div>
                    <div class="hover-product__todayprice">64 990</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </q-carousel-slide>
      <q-carousel-slide :name="4" class="column no-wrap">
        <div class="wrap">
          <div class="proudcts-slider-page__item">
            <div class="proudcts-slider-page__wrapper">
              <div class="proudcts-slider-page__product product">
                <a href="#" class="product__img">
                  <img src="../assets/Catalog/imgItem.webp" alt="not found" />
                </a>
                <div class="product__title">
                  <p>
                    <a href="#"
                      >BH Fitness F1 G6414V <span>Беговая дорожка</span></a
                    >
                  </p>
                </div>
                <div class="product__footer">
                  <div class="product__oldprice">64 990</div>
                  <div class="product__buy">
                    <a href="#" class="product__cart">
                      <div></div>
                    </a>
                    <div class="product__todayprice">64 990</div>
                  </div>
                </div>
              </div>
              <div class="proudcts-slider-page__product-hover hover-product">
                <div class="hover-product__title">
                  BH Fitness F1 G6414V
                  <p>Беговая дорожка</p>
                </div>
                <div class="hover-product__options">
                  <div class="hover-product__option">
                    Тип беговой дорожки:
                    <p>Электрическая</p>
                  </div>
                  <div class="hover-product__option">
                    Скорость движения (км/ч):
                    <p>22</p>
                  </div>
                  <div class="hover-product__option">
                    Складывание:
                    <p>Есть</p>
                  </div>
                </div>
                <a href="#" class="hover-product__cart">
                  <div></div>
                </a>
                <div class="hover-product__footer">
                  <div class="hover-product__oldprice"><span>64 990</span></div>
                  <div class="hover-product__price">
                    <div class="hover-product__button">в наличии</div>
                    <div class="hover-product__todayprice">64 990</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="proudcts-slider-page__item">
            <div class="proudcts-slider-page__wrapper">
              <div class="proudcts-slider-page__product product">
                <a href="#" class="product__img">
                  <img src="../assets/Catalog/imgItem.webp" alt="not found" />
                </a>
                <div class="product__title">
                  <p>
                    <a href="#"
                      >BH Fitness F1 G6414V <span>Беговая дорожка</span></a
                    >
                  </p>
                </div>
                <div class="product__footer">
                  <div class="product__oldprice">64 990</div>
                  <div class="product__buy">
                    <a href="#" class="product__cart">
                      <div></div>
                    </a>
                    <div class="product__todayprice">64 990</div>
                  </div>
                </div>
              </div>
              <div class="proudcts-slider-page__product-hover hover-product">
                <div class="hover-product__title">
                  BH Fitness F1 G6414V
                  <p>Беговая дорожка</p>
                </div>
                <div class="hover-product__options">
                  <div class="hover-product__option">
                    Тип беговой дорожки:
                    <p>Электрическая</p>
                  </div>
                  <div class="hover-product__option">
                    Скорость движения (км/ч):
                    <p>22</p>
                  </div>
                  <div class="hover-product__option">
                    Складывание:
                    <p>Есть</p>
                  </div>
                </div>
                <a href="#" class="hover-product__cart">
                  <div></div>
                </a>
                <div class="hover-product__footer">
                  <div class="hover-product__oldprice"><span>64 990</span></div>
                  <div class="hover-product__price">
                    <div class="hover-product__button">в наличии</div>
                    <div class="hover-product__todayprice">64 990</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </q-carousel-slide>
    </q-carousel>
  </div>
</template>

<script>
import { ref } from "vue";

export default {
  setup() {
    return {
      slide: ref(1),
    };
  },
};
</script>

<style scoped lang="scss">
.wrap {
  display: flex;
  justify-content: space-between;
  @media (max-width: 780px) {
    flex-direction: column;
    align-items: center;
  }
}
.proudcts-slider-page {
  &__wrapper {
    text-align: center;
    max-width: 265px;
    height: 385px;
    position: relative;
  }
  &__product-hover {
    padding: 20px 20px;
    position: absolute;
    top: 0;
    left: 0;
    background-color: rgba(0, 0, 0, 0.84);
    border: 5px solid #f68038;
    width: 100%;
    height: 100%;
  }
  &__item {
    overflow: hidden;
    width: 49%;
    display: inline-block;
    @media (max-width: 780px) {
      width: 100%;
    }
    .hover-product {
      transition-duration: 0.3s;
      left: -100%;
    }
    &:hover {
      .hover-product {
        left: 0%;
      }
      .product__footer {
        display: none;
      }
      .product__title {
        display: none;
      }
    }
  }

  &__product {
    width: 100%;
    height: 100%;
    padding: 20px 17px 20px 17px;
    border: 1px solid #f5f5f5;
    .product__img {
      width: 100%;
      height: 213px;
    }
  }
}
.product {
  &__img {
    display: block;
    width: 225px;
    height: 147px;
    position: relative;
    img {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
    }
  }

  &__title {
    padding: 5px 0 16px 0px;
    a {
      font-family: Roboto-Light;
      font-size: 16px;
      line-height: 24px;
      color: #36949f;
    }
  }

  &__name {
  }

  &__footer {
  }

  &__oldprice {
    text-align: right;
    font-size: 18px;
    line-height: 24px;
    text-decoration: line-through;
    color: #999999;
  }

  &__buy {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  &__cart {
    div {
      display: inline-block;
    }
  }

  &__todayprice {
    font-family: Roboto-Light;
    font-size: 24px;
    line-height: 24px;
    color: #333333;
  }
}
.hover-product {
  display: flex;
  flex-direction: column;
  &__title {
    font-family: Roboto-Black;
    font-size: 16px;
    line-height: 22px;
    color: #ffffff;
    margin: 0 0 29px 0;
    p {
      font-family: Roboto-Light;
      color: #c2c2c2;
    }
  }

  &__options {
  }

  &__option {
    font-family: Roboto-Regular;
    font-size: 14px;
    line-height: 24px;
    color: #ffffff;
    margin: 0 0 12px 0;
    p {
      font-family: Roboto-Black;
      color: #f68038;
      line-height: 18px;
    }
  }

  &__cart {
    display: flex;
    justify-content: center;
    text-align: center;
    flex: 1 1 auto;
    img {
    }
    &_catalog {
      flex: 0 1 auto;
    }
    &_link {
      justify-content: start;
      font-family: Roboto-Light;
      font-size: 14px;
      line-height: 18px;
      color: #ffffff;
      span {
        padding: 0 0 0 31px;
      }
    }
  }

  &__footer {
  }

  &__button {
    background-color: #ffffff;
    padding: 0 10px;
    border-radius: 20px;
    font-family: Roboto-Light;
    font-size: 14px;
    line-height: 18px;
    color: #f68038;
    height: 21px;
  }

  &__price {
    font-family: Roboto-Black;
    font-size: 24px;
    line-height: 24px;
    color: #ffffff;
    display: flex;
    justify-content: space-between;
  }

  &__oldprice {
    font-family: Roboto-Light;
    font-size: 18px;
    text-decoration: line-through;
    color: #999999;
    text-align: right;
    margin: 0 0 3px 0;
  }

  &__todayprice {
    display: flex;
    align-items: flex-end;
  }
}
</style>