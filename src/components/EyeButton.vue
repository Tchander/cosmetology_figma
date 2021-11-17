<template>
  <button class="cos-eye__button">
    Версия для слабовидящих
    <img
      src="../assets/images/header/eye.png"
      alt="eye"
      class="cos-eye__image"
    />
  </button>
</template>

<script>
export default {
  name: "EyeButton",
};
</script>

<style lang="scss" scoped>
.cos-eye__button {
  position: relative;
  font-weight: 500;
  font-size: 14px;
  line-height: 16px;
  text-transform: uppercase;
  color: #fff;
  background: #00868a;
  padding: 13px 15px 13px 51px;
  transition: 0.35s ease;
  &:hover {
    background: #4fbfa5;
  }
  .cos-eye__image {
    position: absolute;
    width: 26px;
    top: 9px;
    left: 14px;
  }
}
</style>
