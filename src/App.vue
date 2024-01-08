<script>
import AppHeader from "./components/AppHeader.vue";
export default {
  components:{
    AppHeader
  }
}
</script>
<template lang="">
  <div class="container">
    <AppHeader></AppHeader>
  </div>
</template>
<style lang="scss" scoped>
  .container{
    max-width: 1200px;
    margin: 0 auto;
  }
</style>