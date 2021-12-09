<template>
  <div class="home">
    <Nav/>
    <homePageConteneur/>
    <contenerMid/>
    <newsletterContainer/>
    <pictoBasContainer/>
    <Footer/>

  </div>
</template>

<script>
import Nav from '../components/nav-footer/Nav.vue';
import homePageConteneur from '../components/homePage/homePageConteneur.vue';
import contenerMid from '../components/homePage/textMid/contenerMid.vue'
import newsletterContainer from '../components/homePage/newsletter/newsletterContainer.vue'
import pictoBasContainer from '../components/homePage/pictoBas/pictoBasContainer.vue'
import Footer from '../components/nav-footer/Footer.vue';


export default {
  name: 'Home',
  components: {
    Nav,
    homePageConteneur,
    contenerMid,
    newsletterContainer,
    pictoBasContainer,
    Footer,

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