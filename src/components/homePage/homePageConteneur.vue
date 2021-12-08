<template>
  <div class="homePageConteneur">
    <titreMain></titreMain>
    <recherche></recherche>
  </div>
</template>

<script lang="ts">

import titreMain from './titreMain.vue';
import recherche from './recherche.vue';

export default {
  name: 'homePageConteneur',
  components: {
    titreMain,
    recherche,
  },  
}

</script>

<style lang="scss">
  .homePageConteneur{
    width: 1024px;
    margin: auto;
    position: relative;
  }
</style>