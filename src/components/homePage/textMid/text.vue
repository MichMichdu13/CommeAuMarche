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
</style>