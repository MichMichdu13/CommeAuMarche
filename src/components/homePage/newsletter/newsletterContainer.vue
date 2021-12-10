<template>
  <div class="newsletterContainer">
      <h4>S’abonner à notre newsleter </h4>
      <p>Vous avez envie d’en découvrir plus sur le système du site ?<br> Abonnez - vous à la newsletter !</p>
      <formNews/>
  </div>
</template>

<script lang="ts">
import formNews from './formNews.vue';

export default {
  name: 'newsletterContainer',
    components: {
        formNews,
  },
}
</script>

<style lang="scss">
.newsletterContainer{
    display: flex;
    align-items: center;
    flex-direction: column;
    h4{
        font: normal normal normal 40px/77px BourtonBase;
        color: #5E6B4F;
        margin-bottom: 70px;
    }
    p{
          text-align: center;
        font: normal normal normal 20px TradeGothicLTPro;
        color: #5E6B4F;
        margin: 0;
    }
}
@media screen and (max-width: 1024px){
   h4{
          font-size: 23px !important;
          margin-bottom: 50px;

      }
    p{
      font-size: 14px !important;
      width: 90%;
    }
}

</style>