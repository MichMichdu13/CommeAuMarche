<template>
  <div class="titreMain">
      <h3 class="titreMain1">Les produits locaux</h3>
      <h3 class="titreMain2">SONT GÉNIAUX</h3>
  </div>
</template>

<script lang="ts">
export default {
  name: 'titreMain',
}
</script>

<style lang="scss">

  .titreMain{
    display: grid;
     grid-template-columns: 250px 100px 200px;
     grid-template-rows: 50px 20px 50px;
      grid-template-areas: 
    "t1 t1 ."
    ". . ."
    ". t2 t2";
    text-align: center;
    margin: 0 0 200px 0;
    .titreMain1{
        color:#5E6B4F ;
        font: normal normal normal 40px/40px TradeGothicLTPro;
        // font-family:"TradeGothicLTPro";  
        grid-area: t1;
    }
    .titreMain2{
        color:#5E6B4F ;
        font-family:"BourtonBase";
        grid-area: t2;
        font-size: 40px;
    }
  }
    @media screen and (max-width: 1024px){
       .titreMain{
         margin: 20px auto 50px auto;
        grid-template-columns: 150px 50px 100px;
        grid-template-rows: 30px 10px 30px;
        .titreMain1{
          font-size: 20px;
        }
        .titreMain2{
          font-size: 20px;
        }
       }
}
</style>