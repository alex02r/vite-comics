<script>
import AppHeader from "./components/AppHeader.vue";
import AppFooter from "./components/AppFooter.vue";
export default {
  components:{
    AppHeader,
    AppFooter
  }
}
</script>
<template lang="">
  <div class="container">
    <AppHeader></AppHeader>
    <AppFooter></AppFooter>
  </div>
</template>
<style lang="scss" scoped>
  .container{
    max-width: 1200px;
    margin: 0 auto;
  }
</style>