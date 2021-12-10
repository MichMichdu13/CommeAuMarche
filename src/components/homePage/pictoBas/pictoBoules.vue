<template>
  <div class="PictoBoule">
      <div class="picto">
        <svg xmlns="http://www.w3.org/2000/svg" width="150" height="100" viewBox="0 0 208.126 137.743">
          <ellipse id="Ellipse_3" data-name="Ellipse 3" cx="96" cy="51.5" rx="96" ry="51.5" transform="translate(0 36.635) rotate(-11)" fill="#c99466" opacity="0.6"/>
        </svg>
        <img :src=imgPictoBas alt="">

      </div>
      <p>{{textPictoBas}}</p>
  </div>
</template>

<script lang="ts">

export default {
  name: 'textMid',
    components: {
  },
  props:{
      textPictoBas: String,
      imgPictoBas: String,
  },
}
</script>

<style lang="scss">

  .PictoBoule{
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 300px;
      p{
        text-align: center;
        font: normal normal normal 20px TradeGothicLTPro;
        color: #5E6B4F;
        margin: 0;
      }
      .picto{
        width: 150px;
        height: 100px;
        position: relative;
        display: flex;
        justify-content: center;
        align-items: center;
        svg{
          position: absolute;
          top: 0;
          left: 0;
          z-index: 0;
        }
        img{
          width: 40px;
          height: 40px;
          z-index: 1;
        }
      }
  }
  @media screen and (max-width: 1024px){
    .PictoBoule{
      width: 150px !important;
      height: 150px !important;
      p{
        font-size: 14px !important;
      }
    }


}
</style>