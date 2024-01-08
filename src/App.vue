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
  <AppHeader></AppHeader>
  <main>
    <h2> --> Content goes here<-- </h2>
  </main>
  <AppFooter></AppFooter>
</template>
<style lang="scss" scoped>
  main{
    background-color: black;
    h2{
      padding: 50px 0;
      color: white;
    }
  }
</style>