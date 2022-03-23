<template>
  <div class="loading">
    <span></span>
  </div>
</template>

<script>
export default {
  name: 'MovieLoading',
}
</script>

<style lang="scss" scoped>
/* Global CSS 적용되어서 따로 설정 안해도 될듯 */

/* .loading {
  height: 100vh;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  @keyframes circle-loading {
    to {
      transform: rotateZ(360deg);
    }
  }
  span {
    display: block;
    width: 70px;
    height: 70px;
    border-radius: 50%;
    border: 2px solid transparent;
    border-top-color: #fff;
    animation: circle-loading 1200ms ease infinite;
  }
} */
</style>