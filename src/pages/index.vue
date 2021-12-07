<template>
  <div class="home">
    <Nav></Nav>
  </div>
</template>

<script>
import Nav from '../components/Nav.vue';

export default {
  name: 'Home',
  components: {
    Nav,
  },
}
</script>

<style lang="scss">
.home {
  color: white;
  height: 100vh;
  width: 100%;

}
</style>