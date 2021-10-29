<template>
  <section class="cos-news">
    <div class="cos-container">
      <div class="cos-news-wrapper">
        <div class="cos-news-content">
          <div class="cos-news-content-btn">
            <a href="#" class="cos-news-content-btn__link">Новости</a>
          </div>
          <div class="cos-news-content__text cos-news-content__text--dark">
            Почему рекомендуется посещать профессионального косметолога. Мнение
            специалистов центра
          </div>
          <div class="cos-news-content__text">
            Стандартизация деятельности клиник в соответствии с ISO 9001:2015.
          </div>
          <div class="cos-news-content__text">
            Индивидуальный подход к каждому пациенту и подбор оптимальных
            косметологических методик.
          </div>
        </div>
        <div class="cos-news-info">
          <div class="cos-news-info__title">
            Почему рекомендуется посещать профессионального косметолога. Мнение
            специалистов центра
          </div>
          <div class="cos-news-info__text">
            Процедуры аппаратной косметологии на оборудовании экспертного класса
            от ведущих мировых производителей могут проводиться в любом возрасте
            и решать широкий спектр проблем: возрастные изменения, покраснения,
            акне и купероз, потеря тонуса и упругости кожи, отечность, целлюлит
            и т. п.
          </div>
          <div class="cos-news-info__text">
            С помощью инъекционных методик мы можем разгладить морщины, провести
            объёмное моделирование, увлажнить кожу, ввести активные вещества в
            поверхностные и средние слои кожи, запустить процессы омоложения.
          </div>
          <div class="cos-news-info__text">
            Лазерное и фотоомоложение помогут запустить процесс синтеза
            собственного коллагена, улучшить светооптические свойства кожи, а
            также получить максимальный эффект подтяжки лица без уколов и
            длительного восстановительного периода.
          </div>
          <div class="cos-news-info__text">
            Курс процедур лазерной эпиляции поможет навсегда избавиться от
            проблемы нежелательных волос.
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "NewsSection",
};
</script>

<style lang="scss" scoped>
.cos-news {
  padding-bottom: 100px;
  .cos-news-wrapper {
    display: flex;
    .cos-news-content {
      background: #4fbfa5;
      width: 40.5861%;
      max-width: 525.5px;
      .cos-news-content-btn {
        margin: 44px 0 40px 40px;
        .cos-news-content-btn__link {
          background: #00868a;
          font-size: 18px;
          line-height: 21px;
          padding: 9px 15px 10px 15px;
          color: #ffffff;
          transition: 0.35s ease;
          &:hover {
            color: #000;
            background: #fff;
          }
        }
      }
      .cos-news-content__text {
        width: 100%;
        padding: 35px 40px;
        font-size: 18px;
        line-height: 150%;
        color: #fff;
        cursor: pointer;
        &--dark {
          background: #00868a;
        }
      }
    }
    .cos-news-info {
      width: 59.4139%;
      background: #e5f3f3;
      padding: 35px 60px;
      .cos-news-info__title {
        font-weight: 700;
        font-size: 24px;
        line-height: 150%;
        margin-bottom: 25px;
      }
      .cos-news-info__text {
        position: relative;
        padding-left: 22px;
        font-size: 14px;
        line-height: 150%;
        margin-bottom: 15px;
        &:after {
          content: "";
          position: absolute;
          top: 6px;
          left: 0;
          display: block;
          width: 6px;
          height: 6px;
          border-radius: 2px;
          background: #00868a;
        }
      }
    }
  }
}
</style>
