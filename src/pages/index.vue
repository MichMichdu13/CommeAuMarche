<template>
  <div class="home">
    <Nav></Nav>
    <homePageConteneur></homePageConteneur>
  </div>
</template>

<script>
import Nav from '../components/nav-footer/Nav.vue';
import homePageConteneur from '../components/homePage/homePageConteneur.vue';

export default {
  name: 'Home',
  components: {
    Nav,
    homePageConteneur,
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