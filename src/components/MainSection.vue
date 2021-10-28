<template>
  <section class="cos-main">
    <div class="cos-container">
      <div class="cos-main-header">
        <ul class="cos-main-header-navigation">
          <li>
            <a href="#" class="cos-main-header-navigation__link"
              >Косметология</a
            >
          </li>
          <li>
            <a href="#" class="cos-main-header-navigation__link"
              >Пластическая хирургия</a
            >
          </li>
          <li>
            <a href="#" class="cos-main-header-navigation__link"
              >Стоматология</a
            >
          </li>
          <li>
            <a href="#" class="cos-main-header-navigation__link"
              >Лазерная медицина</a
            >
          </li>
          <li>
            <a href="#" class="cos-main-header-navigation__link">Контакты</a>
          </li>
        </ul>
        <div class="cos-main-header-appointment">
          <a href="#" class="cos-main-header-appointment__link"
            >Запись на прием</a
          >
        </div>
      </div>
      <div class="cos-main-info">
        <div class="cos-main-info-content">
          <div class="cos-main-info-content__title">Косметология</div>
          <div class="cos-main-info-content__text">
            Современный мир диктует новые каноны жизни: ухоженное лицо и тело,
            стройная, подтянутая фигура — сегодня это неотъемлемые черты
            привлекательной внешности, характеризующие человека благополучного и
            успешного.
          </div>
          <div class="cos-main-info-content__details">
            <a href="#" class="cos-main-info-content__details-btn">подробнее</a>
          </div>
          <div class="cos-main-info-content__arrows">
            <div class="cos-main-info-content__arrows-container">
              <div class="cos-main-info-content__arrows-left">
                <img src="../assets/images/main/arrow_left.png" alt="left" />
              </div>
              <div class="cos-main-info-content__arrows-right">
                <img src="../assets/images/main/arrow_right.png" alt="right" />
              </div>
            </div>
          </div>
        </div>
        <div class="cos-main-info-image">
          <img src="../assets/images/main/main_01.png" alt="img" />
        </div>
      </div>
      <div class="cos-main-footer">
        <div class="cos-main-footer-procedures">
          <a href="#" class="cos-main-footer-procedures__link"
            >Комплексные процедуры</a
          >
        </div>
        <div class="cos-main-footer-learning">
          <a href="#" class="cos-main-footer-learning__link">Центр обучения</a>
        </div>
        <div class="cos-main-footer-vip">
          <a href="#" class="cos-main-footer-vip__link">VIP клиентам</a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "MainSection",
};
</script>

<style lang="scss" scoped>
@mixin footerBtnText {
  font-size: 21px;
  line-height: 150%;
  text-align: center;
  color: #fff;
}
.cos-main {
  background: #4fbfa5;
  .cos-main-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 33px 5px;
    .cos-main-header-navigation {
      display: flex;
      margin-left: 60px;
      li {
        margin-right: 65px;
        .cos-main-header-navigation__link {
          font-size: 18px;
          line-height: 150%;
          color: #fff;
          transition: color 0.35s ease;
          &:hover {
            color: #00868a;
          }
        }
      }
    }
    .cos-main-header-appointment {
      .cos-main-header-appointment__link {
        font-size: 18px;
        line-height: 21px;
        color: #000;
        padding: 9px 15px 10px 15px;
        background: #fff;
        transition: 0.35s ease;
        &:hover {
          color: #fff;
          background: #00868a;
        }
      }
    }
  }
  .cos-main-info {
    display: flex;
    .cos-main-info-content {
      width: 42.271%;
      padding: 133px 0 0 0;
      .cos-main-info-content__title {
        font-weight: 700;
        font-size: 48px;
        line-height: 150%;
        color: #fff;
        margin-bottom: 20px;
      }
      .cos-main-info-content__text {
        line-height: 150%;
        color: #fff;
        width: 100%;
        max-width: 416px;
        margin-bottom: 55px;
      }
      .cos-main-info-content__details {
        margin-bottom: 38px;
        .cos-main-info-content__details-btn {
          font-size: 18px;
          line-height: 21px;
          letter-spacing: 0.05em;
          text-transform: uppercase;
          color: #fff;
          background: #00868a;
          padding: 15px 25px 14px 25px;
          transition: 0.35s ease;
          &:hover {
            background: #fff;
            color: #000;
          }
        }
      }
      .cos-main-info-content__arrows {
        display: flex;
        justify-content: flex-end;
        margin-right: 60px;
        .cos-main-info-content__arrows-container {
          display: flex;
          border: 1px solid #fff;
          cursor: pointer;
          img {
            width: 100%;
            max-width: 30px;
          }
          .cos-main-info-content__arrows-left {
            display: flex;
            align-items: center;
            border-right: 1px solid #fff;
            padding: 25px 15px;
          }
          .cos-main-info-content__arrows-right {
            display: flex;
            align-items: center;
            padding: 25px 15px;
          }
        }
      }
    }
    .cos-main-info-image {
      width: 57.729%;
      img {
        width: 100%;
      }
    }
  }
  .cos-main-footer {
    display: flex;
    cursor: pointer;
    .cos-main-footer-procedures {
      background: #00868a;
      width: 50%;
      padding: 24px 0;
      text-align: center;
      transition: 0.35s ease;
      &:hover {
        background: #fff;
        .cos-main-footer-procedures__link {
          color: #000;
        }
      }
      .cos-main-footer-procedures__link {
        @include footerBtnText;
      }
    }
    .cos-main-footer-learning {
      background: #4fbfa5;
      width: 25%;
      padding: 24px 0;
      text-align: center;
      transition: 0.35s ease;
      &:hover {
        background: #fff;
        .cos-main-footer-learning__link {
          color: #000;
        }
      }
      .cos-main-footer-learning__link {
        @include footerBtnText;
      }
    }
    .cos-main-footer-vip {
      background: #00868a;
      width: 25%;
      padding: 24px 0;
      text-align: center;
      transition: 0.35s ease;
      &:hover {
        background: #fff;
        .cos-main-footer-vip__link {
          color: #000;
        }
      }
      .cos-main-footer-vip__link {
        @include footerBtnText;
      }
    }
  }
}
</style>
