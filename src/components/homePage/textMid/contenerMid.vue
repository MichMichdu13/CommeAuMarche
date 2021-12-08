<template>
  <div class="contenerMid">
      <h1>Comme au marché</h1>
      <div class="textDiv">
          <textMid class="fisrtchild" textMidtitle="Notre but ?" textMidtext="Que les restaurateurs trouvent des producteurs locaux rapidement et facilement."/>
          <textMid textMidtitle="Comment ?" textMidtext="Les restaurateurs renseignent leur besoin, des producteurs locaux leur sont proposés. Ils peuvent consulter les caractéristiques de l’entreprise et les contacter."/>
      </div>
  </div>
</template>

<script lang="ts">
import textMid from './text.vue'

export default {
  name: 'contenerMid',
    components: {
    textMid,
  },
}
</script>

<style lang="scss">

  .contenerMid{
      width: 100%;
      display: flex;
      flex-direction: column;
      align-items: center;
      margin-bottom: 200px;
      h1{
          font: normal normal normal 40px/77px BourtonBase;
          color: #5E6B4F;
          margin: 80px;
          margin-top: 0;
      }
      .textDiv{
          width: 800px;
          height: 200px;
          display: flex;
          align-items: end;
          justify-content: space-between;
          .fisrtchild{
              align-self: flex-start;
          }
      }
  }
</style>