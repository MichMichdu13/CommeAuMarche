<template>
  <div class="homePageConteneur">
    <div class="header">
      <titreMain></titreMain>
      <recherche></recherche>
    </div>
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
    width: 90%;
    margin: auto;
    position: relative;
    .header{
      height: 90vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }
  }
  @media screen and (max-width: 1024px){
    .header{
      height: 70vh !important;
    }
}
</style>