<template>
  <div class="homePageConteneur">
    <titreMain></titreMain>
  </div>
</template>

<script lang="ts">

import titreMain from './titreMain.vue';

export default {
  name: 'homePageConteneur',
  components: {
    titreMain,
  },  
}

</script>

<style lang="scss">
  .homePageConteneur{
    width: 1024px;
    margin: auto;
  }
</style>