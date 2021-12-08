<template>
  <div class="home">
    <Nav></Nav>
    <homePageConteneur></homePageConteneur>
    <contenerMid/>
  </div>
</template>

<script>
import Nav from '../components/nav-footer/Nav.vue';
import homePageConteneur from '../components/homePage/homePageConteneur.vue';
import contenerMid from '../components/homePage/textMid/contenerMid.vue'

export default {
  name: 'Home',
  components: {
    Nav,
    homePageConteneur,
    contenerMid,
  },
}
</script>

<style lang="scss">
.home {
  height: 100vh;
  width: 100%;
  position: relative;
  overflow-x: hidden;

}
</style>