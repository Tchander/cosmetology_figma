<template>
  <header class="cos-header">
    <div class="cos-container">
      <ul class="cos-header-content">
        <li class="cos-header-content__logo">
          <img
            src="../assets/images/header/logo.png"
            alt="MEDI"
            class="cos-header-content__logo-img"
          />
          <img
            src="../assets/images/header/logo_text.png"
            alt="MEDI"
            class="cos-header-content__logo-text_img"
          />
        </li>
        <li class="cos-header-content__phone">+7 (123) 456 78 90</li>
        <li class="cos-header-content__salons">
          <div class="cos-header-content__salons-text">Наши салоны</div>
          <img
            src="../assets/images/header/down_arrow.png"
            alt="arrow"
            class="cos-header-content__salons-arrow"
          />
        </li>
        <li class="cos-header-content__eye">
          <button class="cos-header-content__eye-button">
            Версия для слабовидящих
            <img
              src="../assets/images/header/eye.png"
              alt="eye"
              class="cos-header-content__eye-img"
            />
          </button>
        </li>
        <li class="cos-header-content__icon">
          <a href="#">
            <img src="../assets/images/header/vk.png" alt="vk" />
          </a>
        </li>
        <li class="cos-header-content__icon">
          <a href="#">
            <img src="../assets/images/header/youtube.png" alt="youtube" />
          </a>
        </li>
        <li class="cos-header-content__icon">
          <a href="#">
            <img src="../assets/images/header/facebook.png" alt="facebook" />
          </a>
        </li>
        <li class="cos-header-content__icon">
          <a href="#">
            <img src="../assets/images/header/instagram.png" alt="instagram" />
          </a>
        </li>
      </ul>
    </div>
  </header>
</template>

<script>
export default {
  name: "HeaderSection",
};
</script>

<style lang="scss" scoped>
@mixin text {
  font-weight: 500;
  font-size: 16px;
  line-height: 19px;
}
.cos-header {
  background: #fff;
  .cos-header-content {
    display: flex;
    align-items: center;
    height: 90px;
    li {
      border-right: 1px solid #c4c4c4;
      height: 100%;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    .cos-header-content__logo {
      border-left: 1px solid #c4c4c4;
      width: 20.077%;
      .cos-header-content__logo-img {
        width: 81px;
        height: 54.98px;
      }
      .cos-header-content__logo-text_img {
        width: 100px;
        height: 27.49px;
        margin-left: 10px;
      }
    }
    .cos-header-content__phone {
      width: 14.2857%;
      @include text;
    }
    .cos-header-content__salons {
      width: 15.3668%;
      .cos-header-content__salons-text {
        @include text;
        margin-right: 15px;
      }
      .cos-header-content__salons-arrow {
        cursor: pointer;
      }
    }
    .cos-header-content__eye {
      width: 25.56%;
      .cos-header-content__eye-button {
        position: relative;
        font-weight: 500;
        font-size: 14px;
        line-height: 16px;
        text-transform: uppercase;
        color: #fff;
        background: #00868a;
        padding: 13px 15px 13px 51px;
        .cos-header-content__eye-img {
          position: absolute;
          width: 26px;
          top: 9px;
          left: 14px;
        }
      }
    }
    .cos-header-content__icon {
      width: 6.1776%;
    }
  }
}
</style>
