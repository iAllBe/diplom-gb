<template>
  <div>
    <header class="header">
      <div class="container">
        <div class="header__inner">
          <div class="logo">
            <a href="/" class="logo__link">
              <img
                :src="logoMobileImage"
                alt=""
                class="logo__image logo__image_mobile"
              />
              <img
                :src="logoMobileImage"
                alt=""
                class="logo__image logo__image_tablet"
              />
              <img
                :src="logoDesktopImage"
                alt=""
                class="logo__image logo__image_desktop"
              />
            </a>
          </div>
          <div class="header__cart-menu-wrapper">
            <nav class="menu">
              <button class="menu__button"></button>
              <ul class="menu__list">
                <li class="menu__item">
                  <a href="/" class="menu__link">Масло</a>
                </li>
                <li class="menu__item">
                  <a href="/" class="menu__link">О нас</a>
                </li>
                <li class="menu__item">
                  <a href="/" class="menu__link">Отзывы</a>
                </li>
                <li class="menu__item">
                  <a href="/" class="menu__link">Оплата и доставка</a>
                </li>
                <li class="menu__item">
                  <a href="/" class="menu__link">Контакты</a>
                </li>
              </ul>
            </nav>
            <div class="cart">
              <button class="cart__button"></button>
            </div>
          </div>
        </div>
      </div>
    </header>
    <section class="head">
      <div class="container">
        <div class="head__inner">
          <h1 class="head__title">Наши продукты</h1>
          <div class="head__categories">
            <button
              class="head__categories-button head__categories-button_active"
            >
              Для салата
            </button>
            <button class="head__categories-button">Итальянское</button>
            <button class="head__categories-button">Для мяса</button>
            <button class="head__categories-button">Восточное</button>
          </div>
          <div class="main-slider">
            <div class="main-slider__item">
              <img :src="sliderItemImage1" alt="" class="main-slider__image" />
              <h2 class="main-slider__title">Масло “Для салата”</h2>
              <div class="main-slider__description">
                Название говорит само за себя. Это идеальная заправка, которая
                даже скучной и привычной капусте придаст неповторимый вкус и
                аромат.
              </div>
              <div class="main-slider__quantity">
                <button class="main-slider__quantity-decrement">-</button>
                <div class="main-slider__show-amount">2</div>
                <button class="main-slider__quantity-increment">+</button>
              </div>
              <div class="main-slider__buttons">
                <button class="main-slider__button button">Подробнее</button>
                <button class="main-slider__button button">В корзину</button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <main class="oils">
      <div class="container">
        <div class="oils__inner">
          <h2 class="oils__title">Масло</h2>
          <div class="oil-slider">
            <div class="oil-slider__item oil-slider__item_item-1">
              <div class="oil-slider__image-wrapper">
                <img
                  :src="oilItemImage1"
                  alt=""
                  class="oil-slider__image oil-slider__image_image-1"
                />
              </div>
              <div class="oil-slider__title">Масло “Для салата”</div>
              <div class="oil-slider__description">
                Название говорит само за себя. Это идеальная заправка, которая
                даже скучной и привычной капусте придаст неповторимый вкус и
                аромат.
              </div>
              <div class="oil-slider__compound">
                <b>Состав</b>: оливковое масло холодного отжима, розмарин,
                тимьян, базилик, орегано, чеснок, смесь из 5 перцев.
              </div>
              <div class="oil-slider__quantity">
                <button class="oil-slider__quantity-decrement">-</button>
                <div class="oil-slider__show-amount">2</div>
                <button class="oil-slider__quantity-increment">+</button>
              </div>
              <div class="oil-slider__size-price-wrapper">
                <div class="oil-slider__size">250 мл</div>
                <div class="oil-slider__price-wrapper">
                  <div class="oil-slider__price">275</div>
                  <div class="oil-slider__currency">руб</div>
                </div>
              </div>
              <div class="oil-slider__buttons">
                <button class="oil-slider__button button button_little">
                  В корзину
                </button>
                <button class="oil-slider__button button button_little">
                  Заказать в ТГ
                </button>
              </div>
            </div>
            <div class="oil-slider__item oil-slider__item_item-2">
              <div class="oil-slider__image-wrapper">
                <img :src="oilItemImage2" alt="" class="oil-slider__image" />
              </div>
              <div class="oil-slider__title">Масло “Для салата”</div>
              <div class="oil-slider__description">
                Название говорит само за себя. Это идеальная заправка, которая
                даже скучной и привычной капусте придаст неповторимый вкус и
                аромат.
              </div>
              <div class="oil-slider__compound">
                <b>Состав</b>: оливковое масло холодного отжима, розмарин,
                тимьян, базилик, орегано, чеснок, смесь из 5 перцев.
              </div>
              <div class="oil-slider__quantity">
                <button class="oil-slider__quantity-decrement">-</button>
                <div class="oil-slider__show-amount">2</div>
                <button class="oil-slider__quantity-increment">+</button>
              </div>
              <div class="oil-slider__size-price-wrapper">
                <div class="oil-slider__size">250 мл</div>
                <div class="oil-slider__price-wrapper">
                  <div class="oil-slider__price">275</div>
                  <div class="oil-slider__currency">руб</div>
                </div>
              </div>
              <div class="oil-slider__buttons">
                <button class="oil-slider__button button button_little">
                  В корзину
                </button>
                <button class="oil-slider__button button button_little">
                  Заказать в ТГ
                </button>
              </div>
            </div>
            <div class="oil-slider__item oil-slider__item_item-3">
              <div class="oil-slider__image-wrapper">
                <img :src="oilItemImage3" alt="" class="oil-slider__image" />
              </div>
              <div class="oil-slider__title">Масло “Для салата”</div>
              <div class="oil-slider__description">
                Название говорит само за себя. Это идеальная заправка, которая
                даже скучной и привычной капусте придаст неповторимый вкус и
                аромат.
              </div>
              <div class="oil-slider__compound">
                <b>Состав</b>: оливковое масло холодного отжима, розмарин,
                тимьян, базилик, орегано, чеснок, смесь из 5 перцев.
              </div>
              <div class="oil-slider__quantity">
                <button class="oil-slider__quantity-decrement">-</button>
                <div class="oil-slider__show-amount">2</div>
                <button class="oil-slider__quantity-increment">+</button>
              </div>
              <div class="oil-slider__size-price-wrapper">
                <div class="oil-slider__size">250 мл</div>
                <div class="oil-slider__price-wrapper">
                  <div class="oil-slider__price">275</div>
                  <div class="oil-slider__currency">руб</div>
                </div>
              </div>
              <div class="oil-slider__buttons">
                <button class="oil-slider__button button button_little">
                  В корзину
                </button>
                <button class="oil-slider__button button button_little">
                  Заказать в ТГ
                </button>
              </div>
            </div>
            <div class="oil-slider__item oil-slider__item_item-4">
              <div class="oil-slider__image-wrapper">
                <img :src="oilItemImage4" alt="" class="oil-slider__image" />
              </div>
              <div class="oil-slider__title">Масло “Для салата”</div>
              <div class="oil-slider__description">
                Название говорит само за себя. Это идеальная заправка, которая
                даже скучной и привычной капусте придаст неповторимый вкус и
                аромат.
              </div>
              <div class="oil-slider__compound">
                <b>Состав</b>: оливковое масло холодного отжима, розмарин,
                тимьян, базилик, орегано, чеснок, смесь из 5 перцев.
              </div>
              <div class="oil-slider__quantity">
                <button class="oil-slider__quantity-decrement">-</button>
                <div class="oil-slider__show-amount">2</div>
                <button class="oil-slider__quantity-increment">+</button>
              </div>
              <div class="oil-slider__size-price-wrapper">
                <div class="oil-slider__size">250 мл</div>
                <div class="oil-slider__price-wrapper">
                  <div class="oil-slider__price">275</div>
                  <div class="oil-slider__currency">руб</div>
                </div>
              </div>
              <div class="oil-slider__buttons">
                <button class="oil-slider__button button button_little">
                  В корзину
                </button>
                <button class="oil-slider__button button button_little">
                  Заказать в ТГ
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </main>
    <section class="about">
      <div class="container">
        <div class="about__inner">
          <h2 class="about__title">О нас</h2>
          <div class="who-we">
            <div class="who-we__image-wrapper">
              <div class="who-we__image"></div>
              <div class="who-we__mount"></div>
            </div>
            <div class="who-we__description">
              <h3 class="who-we__title">Кто мы</h3>
              <div class="who-we__text">
                Мы пара: Таня и Рома и мы создатели пряного оливкового масла
                R.olio. Предыстория: Так сложилось в нашей паре, что готовит у
                нас Рома, он очень увлечен кулинарией и каждый раз придумывает
                что-то новенькое. Накануне прошлого Нового года, мы готовили
                подарки нашим друзьям и родственникам. Нам захотелось к подаркам
                добавить что-то необычное, от себя. И к нам пришла идея, Рома
                готовил вкуснейшее пряное оливковое масло для своих рецептов,
                добавлял розмарин, тимьян, чеснок, разные виды перцев...каждый
                раз получался новый неповторимый вкус.
              </div>
            </div>
          </div>
          <div class="who-do">
            <div class="who-do__image-wrapper">
              <div class="who-do__image"></div>
              <div class="who-do__mount"></div>
            </div>
            <div class="who-do__description">
              <h3 class="who-do__title">Что мы делаем</h3>
              <div class="who-do__text">
                И мы решили сделать такое масло, как добавление к подарку. Надо
                сказать, что наши близкие оценили презент и просили снова и
                снова сделать им такое масло. И появилась идея: почему бы не
                попробовать запустить такое масло в продажу? Рома долго выверял
                рецепты, я разрабатывала дизайн этикеток и искала поставщиков. И
                вот мы готовы представить его вам! Мы старались сделать наше
                масло максимально доступным, при этом не потеряв в качестве.
                Стоимость бутылки(250мл) - всего 115грн.
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="recall">
      <div class="container">
        <div class="recall__inner">
          <h2 class="recall__title">Отзывы</h2>
          <div class="recall-slider">
            <div class="recall-slider__item">
              <div class="recall-slider__image recall-slider__image-1"></div>
            </div>
            <div class="recall-slider__item">
              <div class="recall-slider__image recall-slider__image-2"></div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="delivery">
      <div class="delivery__mount"></div>
      <h2 class="delivery__title">Доставка</h2>
      <div class="delivery__inner">
        <div class="container">
          <div class="causes">
            <div class="causes__item">
              <div class="causes__images causes__images-1"></div>
              <div class="causes__text">Новая почта</div>
            </div>
            <div class="causes__item">
              <div class="causes__images causes__images-2"></div>
              <div class="causes__text">Почта</div>
            </div>
            <div class="causes__item">
              <div class="causes__images causes__images-3"></div>
              <div class="causes__text">Самовывоз</div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="payment">
      <h2 class="payment__title">Оплата</h2>
      <div class="payment__inner">
        <div class="container">
          <div class="causes">
            <div class="causes__item">
              <div class="causes__images causes__images-1"></div>
              <div class="causes__text">Наложенный платёж</div>
            </div>
            <div class="causes__item">
              <div class="causes__images causes__images-1"></div>
              <div class="causes__text">Приват24</div>
            </div>
            <div class="causes__item">
              <div class="causes__images causes__images-1"></div>
              <div class="causes__text">Наличными при самовывозе</div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="contacts">
      <div class="contacts__inner">
        <div class="container">
          <h2 class="contacts__title">Контакты</h2>
          <div class="contacts__image"></div>
          <div class="contacts-list">
            <div class="contacts-list__item">
              <div class="contacts-list__image contacts-list__image-1"></div>
              <a href="tel:+380661143558" class="contacts-list__data"
                >+38 (066) 11-43-558</a
              >
            </div>
            <div class="contacts-list__item">
              <div class="contacts-list__image contacts-list__image-2"></div>
              <a href="/" class="contacts-list__data"
                >https://www.vk.com/r.olio8/</a
              >
            </div>
            <div class="contacts-list__item">
              <div class="contacts-list__image contacts-list__image-3"></div>
              <a href="/" class="contacts-list__data">
                https://www.ok/r.olio_/
              </a>
            </div>
            <div class="contacts-list__item">
              <div class="contacts-list__image contacts-list__image-4"></div>
              <a href="/" class="contacts-list__data">https://t.me/r_olio</a>
            </div>
            <div class="contacts-list__item">
              <div class="contacts-list__image contacts-list__image-5"></div>
              <a href="tel:+380661143558" class="contacts-list__data"
                >+38 (066) 11-43-558</a
              >
            </div>
            <button class="contacts-list__button button">Написать нам</button>
          </div>
        </div>
      </div>
    </section>
    <footer class="footer">
      <div class="footer__inner">
        <div class="container">
          <a href="/" class="footer__logo-link"> </a>
          <nav class="menu-footer">
            <ul class="menu-footer__list">
              <li class="menu-footer__item">
                <a href="/" class="menu-footer__link">Масло</a>
              </li>
              <li class="menu-footer__item">
                <a href="/" class="menu-footer__link">О нас</a>
              </li>
              <li class="menu-footer__item">
                <a href="/" class="menu-footer__link">Отзывы</a>
              </li>
              <li class="menu-footer__item">
                <a href="/" class="menu-footer__link">Оплата и доставка</a>
              </li>
              <li class="menu-footer__item">
                <a href="/" class="menu-footer__link">Контакты</a>
              </li>
            </ul>
          </nav>
          <div class="footer__links">
            <a href="/" class="footer__links-item footer__links-item-1"> </a>
            <a href="/" class="footer__links-item footer__links-item-2"> </a>
            <a href="/" class="footer__links-item footer__links-item-3"> </a>
            <a
              href="tel:+380661143558"
              class="footer__links-item footer__links-item-4"
            >
            </a>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: "HomeView",
  components: {},
  data() {
    return {
      logoMobileImage: require("@/assets/img/logo-mobile.png"),
      logoTabletImage: require("@/assets/img/logo-tablet.png"),
      logoDesktopImage: require("@/assets/img/logo-desktop.png"),
      sliderItemImage1: require("@/assets/img/slide-item-1.png"),
      oilItemImage1: require("@/assets/img/oils-item-1.png"),
      oilItemImage2: require("@/assets/img/oils-item-2.png"),
      oilItemImage3: require("@/assets/img/oils-item-3.png"),
      oilItemImage4: require("@/assets/img/oils-item-4.png"),
    };
  },
  created() {},
};
</script>

<style lang="scss"></style>
