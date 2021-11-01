<template>
  <section class="cos-contacts">
    <div class="cos-container">
      <div class="cos-contacts-wrapper">
        <div class="cos-contacts-services">
          <div class="cos-contacts-services__item">
            <div class="cos-contacts-services__item__title">Услуги</div>
            <ul class="cos-contacts-services__item-list">
              <li>
                <a href="#" class="cos-contacts-services__item-list__link"
                  >Косметология</a
                >
              </li>
              <li>
                <a href="#" class="cos-contacts-services__item-list__link"
                  >Пластическая хирургия</a
                >
              </li>
              <li>
                <a href="#" class="cos-contacts-services__item-list__link"
                  >Стоматология</a
                >
              </li>
              <li>
                <a href="#" class="cos-contacts-services__item-list__link"
                  >Лазерная медицина</a
                >
              </li>
            </ul>
          </div>
          <div class="cos-contacts-services__item">
            <div class="cos-contacts-services__item__title">Услуги</div>
            <ul class="cos-contacts-services__item-list">
              <li>
                <a href="#" class="cos-contacts-services__item-list__link"
                  >Косметология</a
                >
              </li>
              <li>
                <a href="#" class="cos-contacts-services__item-list__link"
                  >Пластическая хирургия</a
                >
              </li>
              <li>
                <a href="#" class="cos-contacts-services__item-list__link"
                  >Стоматология</a
                >
              </li>
              <li>
                <a href="#" class="cos-contacts-services__item-list__link"
                  >Лазерная медицина</a
                >
              </li>
            </ul>
          </div>
          <div class="cos-contacts-services__item">
            <div class="cos-contacts-services__item__title">Услуги</div>
            <ul class="cos-contacts-services__item-list">
              <li>
                <a href="#" class="cos-contacts-services__item-list__link"
                  >Косметология</a
                >
              </li>
              <li>
                <a href="#" class="cos-contacts-services__item-list__link"
                  >Пластическая хирургия</a
                >
              </li>
              <li>
                <a href="#" class="cos-contacts-services__item-list__link"
                  >Стоматология</a
                >
              </li>
              <li>
                <a href="#" class="cos-contacts-services__item-list__link"
                  >Лазерная медицина</a
                >
              </li>
            </ul>
          </div>
          <div class="cos-contacts-services__item">
            <div class="cos-contacts-services__item__title">Услуги</div>
            <ul class="cos-contacts-services__item-list">
              <li>
                <a href="#" class="cos-contacts-services__item-list__link"
                  >Косметология</a
                >
              </li>
              <li>
                <a href="#" class="cos-contacts-services__item-list__link"
                  >Пластическая хирургия</a
                >
              </li>
              <li>
                <a href="#" class="cos-contacts-services__item-list__link"
                  >Стоматология</a
                >
              </li>
              <li>
                <a href="#" class="cos-contacts-services__item-list__link"
                  >Лазерная медицина</a
                >
              </li>
            </ul>
          </div>
          <div class="cos-contacts-services__item">
            <div class="cos-contacts-services__item__title">Услуги</div>
            <ul class="cos-contacts-services__item-list">
              <li>
                <a href="#" class="cos-contacts-services__item-list__link"
                  >Косметология</a
                >
              </li>
              <li>
                <a href="#" class="cos-contacts-services__item-list__link"
                  >Пластическая хирургия</a
                >
              </li>
              <li>
                <a href="#" class="cos-contacts-services__item-list__link"
                  >Стоматология</a
                >
              </li>
              <li>
                <a href="#" class="cos-contacts-services__item-list__link"
                  >Лазерная медицина</a
                >
              </li>
            </ul>
          </div>
          <div class="cos-contacts-services__item">
            <div class="cos-contacts-services__item__title">Услуги</div>
            <ul class="cos-contacts-services__item-list">
              <li>
                <a href="#" class="cos-contacts-services__item-list__link"
                  >Косметология</a
                >
              </li>
              <li>
                <a href="#" class="cos-contacts-services__item-list__link"
                  >Пластическая хирургия</a
                >
              </li>
              <li>
                <a href="#" class="cos-contacts-services__item-list__link"
                  >Стоматология</a
                >
              </li>
              <li>
                <a href="#" class="cos-contacts-services__item-list__link"
                  >Лазерная медицина</a
                >
              </li>
            </ul>
          </div>
        </div>
        <div class="cos-contacts-info">
          <div class="cos-contacts-info__item">
            <div class="cos-contacts-info__item__label">телефон</div>
            <div class="cos-contacts-info__item__text">+7 (812) 123-45-67</div>
          </div>
          <div class="cos-contacts-info__item">
            <div class="cos-contacts-info__item__label">адрес</div>
            <div class="cos-contacts-info__item__text">
              Невский пр. 140, пом. 10
            </div>
            <div class="cos-contacts-info__item-btn">
              <a href="#" class="cos-contacts-info__item-btn__link"
                >как проехать?</a
              >
            </div>
          </div>
          <div class="cos-contacts-info__item">
            <div class="cos-contacts-info__item__label">адрес</div>
            <div class="cos-contacts-info__item__text">Большой пр. 12</div>
            <div class="cos-contacts-info__item-btn">
              <a href="#" class="cos-contacts-info__item-btn__link"
                >как проехать?</a
              >
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "ContactsSection",
};
</script>

<style lang="scss" scoped>
.cos-contacts {
  padding-bottom: 80px;
  .cos-contacts-wrapper {
    display: flex;
    justify-content: space-between;
    padding-right: 68px;
    .cos-contacts-services {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      width: 81%;
      .cos-contacts-services__item {
        width: 30%;
        margin-bottom: 30px;
        .cos-contacts-services__item__title {
          font-weight: 700;
          font-size: 21px;
          line-height: 150%;
          color: #000;
          margin-bottom: 20px;
        }
        .cos-contacts-services__item-list {
          li {
            margin-bottom: 15px;
            .cos-contacts-services__item-list__link {
              line-height: 150%;
              color: #000;
            }
          }
        }
      }
    }
    .cos-contacts-info {
      width: 19%;
      max-width: 238px;
      .cos-contacts-info__item {
        .cos-contacts-info__item__label {
          color: #bfbfbf;
          font-size: 11px;
          line-height: 150%;
          letter-spacing: 0.05em;
          text-transform: uppercase;
          margin-bottom: 10px;
        }
        .cos-contacts-info__item__text {
          font-weight: 700;
          font-size: 21px;
          line-height: 150%;
          color: #000;
          margin-bottom: 30px;
        }
        .cos-contacts-info__item-btn {
          margin-bottom: 44px;
          .cos-contacts-info__item-btn__link {
            padding: 15px 25px 14px 25px;
            background: #00868a;
            line-height: 16px;
            letter-spacing: 0.05em;
            text-transform: uppercase;
            color: #fff;
            transition: 0.35s ease;
            &:hover {
              background: #4fbfa5;
            }
          }
        }
      }
    }
  }
}
</style>
