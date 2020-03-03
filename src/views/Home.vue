<template>
  <div class="about">
      <landing-page></landing-page>
       
  </div>
</template>

<script>

import LandingPage from "@/components/LandingPage.vue";
export default {
  name:'About',
  components:{
    LandingPage
  }
}
</script>

<style lang="scss" scoped>
h1{
  color: red;
}
</style>