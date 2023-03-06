<template lang="">
  <div>
    <Header />
    đây là trang admin
    <RouterView> </RouterView>
  </div>
</template>
<script>
import Header from "../components/Header.vue"
export default {
  components: {
    Header
  }
};
</script>
<style lang=""></style>
