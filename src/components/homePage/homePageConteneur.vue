<template>
  <div class="homePageConteneur">
    <titreMain></titreMain>
    <recherche></recherche>
    <img src="images/sac.png" alt="sac" class="sac">
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
    .sac{
      position: absolute;
      top: 20px;
      right: 150px;
      width: 250px;
    }
  }
</style>