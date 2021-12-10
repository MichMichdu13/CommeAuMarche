<template>
  <div class="textMid">
      <p>{{textMidtitle}}</p>
      <p>{{textMidtext}}</p>
  </div>
</template>

<script lang="ts">

export default {
  name: 'textMid',
    components: {
  },
  props:{
      textMidtitle: String,
      textMidtext: String,
  },
}
</script>

<style lang="scss">

  .textMid{
      width: 300px;
      p{
          text-align: center;
        font: normal normal normal 20px TradeGothicLTPro;
        color: #5E6B4F;
        margin: 0;
      }
  }
@media screen and (max-width: 1024px){
   .textMid{
     margin-bottom: 30px !important;
     p{
       margin: 10px !important;
     }
   }
}
</style>