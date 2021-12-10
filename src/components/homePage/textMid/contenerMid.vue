<template>
  <div class="contenerMid">
      <h1>Comme au marché</h1>
      <div class="textDiv">
          <textMid class="fisrtchild" textMidtitle="Notre but ?" textMidtext="Que les restaurateurs trouvent des producteurs locaux rapidement et facilement."/>
          <textMid textMidtitle="Comment ?" textMidtext="Les restaurateurs renseignent leur besoin, des producteurs locaux leur sont proposés. Ils peuvent consulter les caractéristiques de l’entreprise et les contacter."/>
      </div>
      <svg xmlns="http://www.w3.org/2000/svg" width="1000" height="600" viewBox="0 0 1735.416 1026.843">
        <ellipse id="Ellipse_2" data-name="Ellipse 2" cx="813" cy="365" rx="813" ry="365" transform="translate(0 310.255) rotate(-11)" fill="#c99466" opacity="0.6"/>
      </svg>

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
      position: relative;
      svg{
          position: absolute;
          left: 0;
          bottom: 0;
          transform: translate(-70%, 70%);
      }
      h1{
          font: normal normal normal 40px/77px BourtonBase;
          color: #5E6B4F;
          margin: 80px;
          margin-top: 0;
          text-align: center;
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

@media screen and (max-width: 1024px){
   h1{
          font-size: 23px !important;
          margin: 40px !important;

      }
    svg{
      width: 100% !important;
      bottom: 150% !important;
    }
    .textDiv{

          flex-direction: column !important;
          justify-content: none !important;
          align-items: center !important;
          .fisrtchild{
              align-self: center !important;
          }
      }

}
</style>