<template>
  <section class="cos-actual">
    <div class="cos-container">
      <div class="cos-actual-title">Актуальные спецпредложения</div>
      <div class="cos-actual-cards">
        <div class="cos-actual-cards__item">
          <div class="cos-actual-cards__item-content">
            <img src="../assets/images/actual/actual_01.png" alt="01" />
            <div class="cos-actual-cards__item-content-btn">
              <a href="#" class="cos-actual-cards__item-content-btn__link"
                >Косметология</a
              >
            </div>
          </div>
          <div class="cos-actual-cards__item-info">
            <div class="cos-actual-cards__item-info__text">
              Лазерное и фотоомоложение
            </div>
            <div class="cos-actual-cards__item-info-more">
              <div class="cos-actual-cards__item-info-more__arrow-right">
                <img
                  src="../assets/images/actual/arrow-right.png"
                  alt="arrow"
                />
              </div>
            </div>
          </div>
        </div>
        <div class="cos-actual-cards__item">
          <div class="cos-actual-cards__item-content">
            <img src="../assets/images/actual/actual_02.png" alt="02" />
            <div class="cos-actual-cards__item-content-btn">
              <a href="#" class="cos-actual-cards__item-content-btn__link"
                >Косметология</a
              >
            </div>
          </div>
          <div class="cos-actual-cards__item-info">
            <div class="cos-actual-cards__item-info__text">
              Лазерное и фотоомоложение
            </div>
            <div class="cos-actual-cards__item-info-more">
              <div class="cos-actual-cards__item-info-more__arrow-right">
                <img
                  src="../assets/images/actual/arrow-right.png"
                  alt="arrow"
                />
              </div>
            </div>
          </div>
        </div>
        <div class="cos-actual-cards__item">
          <div class="cos-actual-cards__item-content">
            <img src="../assets/images/actual/actual_03.png" alt="03" />
            <div class="cos-actual-cards__item-content-btn">
              <a href="#" class="cos-actual-cards__item-content-btn__link"
                >Косметология</a
              >
            </div>
          </div>
          <div class="cos-actual-cards__item-info">
            <div class="cos-actual-cards__item-info__text">
              Лазерное и фотоомоложение
            </div>
            <div class="cos-actual-cards__item-info-more">
              <div class="cos-actual-cards__item-info-more__arrow-right">
                <img
                  src="../assets/images/actual/arrow-right.png"
                  alt="arrow"
                />
              </div>
            </div>
          </div>
        </div>
        <div class="cos-actual-cards__item">
          <div class="cos-actual-cards__item-content">
            <img src="../assets/images/actual/actual_04.png" alt="04" />
            <div class="cos-actual-cards__item-content-btn">
              <a href="#" class="cos-actual-cards__item-content-btn__link"
                >Косметология</a
              >
            </div>
          </div>
          <div class="cos-actual-cards__item-info">
            <div class="cos-actual-cards__item-info__text">
              Лазерное и фотоомоложение
            </div>
            <div class="cos-actual-cards__item-info-more">
              <div class="cos-actual-cards__item-info-more__arrow-right">
                <img
                  src="../assets/images/actual/arrow-right.png"
                  alt="arrow"
                />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "ActualSection",
};
</script>

<style lang="scss" scoped>
.cos-actual {
  background: #e5f3f3;
  padding-top: 80px;
  height: 320px;
  margin-bottom: 350px;
  .cos-actual-title {
    font-weight: 700;
    font-size: 48px;
    line-height: 150%;
    text-align: center;
    color: #00868a;
    margin-bottom: 60px;
  }
  .cos-actual-cards {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    .cos-actual-cards__item {
      width: 100%;
      max-width: 306px;
      .cos-actual-cards__item-content {
        position: relative;
        img {
          width: 100%;
        }
        .cos-actual-cards__item-content-btn {
          position: absolute;
          top: 31px;
          left: 30px;
          .cos-actual-cards__item-content-btn__link {
            padding: 9px 15px 10px 15px;
            background: #4fbfa5;
            font-size: 18px;
            line-height: 21px;
            color: #ffffff;
            transition: 0.35s ease;
            &:hover {
              background: #00868a;
            }
          }
        }
      }
      .cos-actual-cards__item-info {
        background: #00868a;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 25px 30px;
        .cos-actual-cards__item-info__text {
          font-weight: 700;
          font-size: 21px;
          line-height: 150%;
          color: #ffffff;
          width: 100%;
          max-width: 181px;
        }
        .cos-actual-cards__item-info-more {
          display: flex;
          cursor: pointer;
          .cos-actual-cards__item-info-more__arrow-right {
            display: flex;
            align-items: center;
            border: 1px solid #fff;
            padding: 20px 15px;
          }
        }
      }
    }
  }
}
</style>
