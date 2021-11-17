<template>
  <footer class="cos-footer">
    <div class="cos-container">
      <div class="cos-footer-wrapper">
        <div class="cos-footer-info">
          <div class="cos-footer-info__copyright">
            (c) 2021. Центр космелогии. Все права защищены. Наши сертификаты на
            осуществление деятельности. Патенты на использование технологий.
          </div>
          <div class="cos-footer-info__politics">
            <a href="#">Политика конфиденциальности</a>
          </div>
        </div>
        <div class="cos-footer-links">
          <div class="cos-footer-links-eye">
            <div class="cos-footer-links-eye__button">
              <eye-button />
            </div>
          </div>
          <div class="cos-footer-links-icons">
            <div class="cos-footer-links-icons__icon">
              <a href="#">
                <img src="../assets/images/header/vk.png" alt="vk" />
              </a>
            </div>
            <div class="cos-footer-links-icons__icon">
              <a href="#">
                <img src="../assets/images/header/youtube.png" alt="youtube" />
              </a>
            </div>
            <div class="cos-footer-links-icons__icon">
              <a href="#">
                <img
                  src="../assets/images/header/facebook.png"
                  alt="facebook"
                />
              </a>
            </div>
            <div class="cos-footer-links-icons__icon">
              <a href="#">
                <img
                  src="../assets/images/header/instagram.png"
                  alt="instagram"
                />
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
import EyeButton from "@/components/EyeButton";
export default {
  name: "FooterSection",
  components: { EyeButton },
};
</script>

<style lang="scss" scoped>
.cos-footer-wrapper {
  display: flex;
  border-top: 1px solid #c4c4c4;
  border-left: 1px solid #c4c4c4;
  .cos-footer-info {
    width: 50%;
    display: flex;
    border-right: 1px solid #c4c4c4;
    .cos-footer-info__copyright {
      width: 51%;
      padding: 20px 0 16px 25px;
      font-size: 12px;
      font-weight: 400;
      line-height: 150%;
      color: #000;
    }
    .cos-footer-info__politics {
      width: 49%;
      display: flex;
      align-items: center;
      justify-content: center;
      a {
        font-size: 12px;
        font-weight: 400;
        line-height: 150%;
        color: #000;
        transition: 0.35s ease;
        &:hover {
          text-decoration-line: underline;
        }
      }
    }
  }
  .cos-footer-links {
    width: 50%;
    display: flex;
    .cos-footer-links-eye {
      width: 51%;
      display: flex;
      align-items: center;
      justify-content: center;
      border-right: 1px solid #c4c4c4;
    }
    .cos-footer-links-icons {
      width: 49%;
      display: flex;
      align-items: center;
      justify-content: center;
      .cos-footer-links-icons__icon {
        width: 25%;
        display: flex;
        align-items: center;
        justify-content: center;
        border-right: 1px solid #c4c4c4;
        height: 100%;
      }
    }
  }
}
</style>
