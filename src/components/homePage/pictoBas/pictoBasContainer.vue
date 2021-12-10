<template>
  <div class="pictoBasContainer">
      <pictoBas textPictoBas="Produits locaux" imgPictoBas="images/emplacement.png"/>
      <pictoBas textPictoBas="Tous les producteurs sont vérifiés" imgPictoBas="images/verif.png"/>
      <pictoBas textPictoBas="Entreprise eco-responsable" imgPictoBas="images/echoPicto.png"/>
  </div>
</template>

<script lang="ts">
import pictoBas from './pictoBoules.vue';

export default {
  name: 'pictoBasContainer',
    components: {
        pictoBas,
  },
}
</script>

<style lang="scss">
.pictoBasContainer{
    width: 1024px;
    margin: 50px auto 100px auto;

    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;

}
  @media screen and (max-width: 1024px){
.pictoBasContainer{
  width: 150px !important;
  flex-direction: column !important;
}


}   

</style>