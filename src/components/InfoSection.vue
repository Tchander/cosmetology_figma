<template>
  <section class="cos-info">
    <div class="cos-container">
      <div class="cos-info-wrapper">
        <div class="cos-info-innovations">
          <div class="cos-info-innovations-content">
            <div class="cos-info-innovations-content-btn">
              <a href="#" class="cos-info-innovations-content-btn__link"
                >Инновации</a
              >
            </div>
            <div class="cos-info-innovations-content__text">
              Мы практикуем новый курс процедур аппаратной косметологии
            </div>
            <div class="cos-info-innovations-content-more">
              <div class="cos-info-innovations-more-content__arrow-right">
                <img src="../assets/images/info/arrow-right.png" alt="arrow" />
              </div>
              <a href="#" class="cos-info-innovations-content-more__link"
                >Подробнее</a
              >
            </div>
          </div>
          <div class="cos-info-innovations__image">
            <img src="../assets/images/info/innovations_img.png" alt="image" />
          </div>
        </div>
        <div class="cos-info-beauty">
          <div class="cos-info-beauty-btn">
            <a href="#" class="cos-info-beauty-btn__link">Эстетика красоты</a>
          </div>
          <div class="cos-info-beauty-content">
            <ul>
              <li class="cos-info-beauty-content-item">
                <div class="cos-info-beauty-content-item__number">78</div>
                <div class="cos-info-beauty-content-item__text">
                  Современных центра в странах СНГ
                </div>
              </li>
              <li class="cos-info-beauty-content-item">
                <div class="cos-info-beauty-content-item__number">78</div>
                <div class="cos-info-beauty-content-item__text">
                  Современных центра в странах СНГ
                </div>
              </li>
              <li
                class="
                  cos-info-beauty-content-item cos-info-beauty-content-item--big
                "
              >
                <div class="cos-info-beauty-content-item__number">20</div>
                <div class="cos-info-beauty-content-item__text">
                  Уникальных патентов<br />в области косметологии
                </div>
              </li>
              <li class="cos-info-beauty-content-item">
                <div class="cos-info-beauty-content-item__number">78</div>
                <div class="cos-info-beauty-content-item__text">
                  Современных центра в странах СНГ
                </div>
              </li>
            </ul>
            <img
              class="cos-info-beauty-content__image"
              src="../assets/images/info/patent.png"
              alt="patent"
            />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "InfoSection",
};
</script>

<style lang="scss" scoped>
.cos-info-wrapper {
  display: flex;
  padding: 80px 0;
  .cos-info-innovations {
    width: 50%;
    padding-right: 122px;
    .cos-info-innovations-content {
      background: #00868a;
      padding: 35px 40px 45px 40px;
      .cos-info-innovations-content-btn {
        margin-bottom: 40px;
        .cos-info-innovations-content-btn__link {
          background: #4fbfa5;
          padding: 9px 15px 10px 15px;
          font-size: 18px;
          line-height: 21.19px;
          color: #fff;
          transition: 0.35s ease;
          &:hover {
            color: #000;
            background: #fff;
          }
        }
      }
      .cos-info-innovations-content__text {
        font-size: 30px;
        line-height: 150%;
        color: #ffffff;
        margin-bottom: 25px;
      }
      .cos-info-innovations-content-more {
        display: flex;
        cursor: pointer;
        .cos-info-innovations-more-content__arrow-right {
          display: flex;
          align-items: center;
          border: 1px solid #fff;
          padding: 20px 15px;
        }
        .cos-info-innovations-content-more__link {
          display: flex;
          align-items: center;
          font-weight: 700;
          font-size: 16px;
          line-height: 150%;
          letter-spacing: 0.05em;
          text-transform: uppercase;
          color: #fff;
          margin-left: 20px;
        }
      }
    }
    .cos-info-innovations__image {
      img {
        width: 100%;
      }
    }
  }
  .cos-info-beauty {
    width: 50%;
    padding: 35px 0 60px 0;
    .cos-info-beauty-btn {
      margin-bottom: 54px;
      .cos-info-beauty-btn__link {
        background: #4fbfa5;
        padding: 9px 15px 10px 15px;
        font-size: 18px;
        line-height: 21.19px;
        color: #fff;
        transition: 0.35s ease;
        &:hover {
          background: #00868a;
        }
      }
    }
    .cos-info-beauty-content {
      position: relative;
      ul {
        position: absolute;
        top: 0;
        left: 0;
        z-index: 2;
        .cos-info-beauty-content-item {
          color: #b2b2b2;
          display: flex;
          margin-bottom: 15px;
          .cos-info-beauty-content-item__number {
            font-size: 48px;
            display: flex;
            align-items: center;
            line-height: 150%;
          }
          .cos-info-beauty-content-item__text {
            width: 100%;
            max-width: 144px;
            margin-left: 20px;
            line-height: 150%;
            display: flex;
            align-items: center;
            margin-bottom: 4px;
          }
          &--big {
            margin-top: 20px;
            .cos-info-beauty-content-item__number {
              font-size: 96px;
              color: #00868a;
              display: flex;
              align-items: center;
              line-height: 150%;
            }
            .cos-info-beauty-content-item__text {
              width: 100%;
              max-width: 319px;
              font-size: 28px;
              color: #000;
              margin-left: 30px;
              line-height: 150%;
              display: flex;
              align-items: center;
              margin-bottom: 10px;
            }
          }
        }
      }
      .cos-info-beauty-content__image {
        position: absolute;
        top: 8px;
        right: 0;
        z-index: 1;
        max-width: 306px;
        width: 100%;
      }
    }
  }
}
</style>
