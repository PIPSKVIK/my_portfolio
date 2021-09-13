<template>
  <div class="main-block">Будущее портфолио фотографа.</div>
</template>

<script>
export default {
  name: 'MainPage',
}
</script>

<style lang="scss" scoped>
.main-block {
  height: 300px;
  background: purple;
  @include md-desktop {
    background: green;
  }
}
</style>
