<template>
  <div class="footer">
      <div class="footerContainer">
            <img src="images/comme-au-marche.png" alt="logo-commme-au-marché" class="logoFooter">
            <div class="footerNav">
                <p>Copyright © 2021 Comme au marché</p>
                <a href=""><img src="images/instaPicto.png" alt="picto Instagram"></a>
                <a href=""><img src="images/facebook.png" alt="Picto facebook"></a>
                <div class="separateur"></div>
                <a href="">Contact</a>
                <a href="">Politique de confidentialité</a>
                <a href="">Mentions légales</a>
            </div>
      </div>
  </div>
</template>

<script lang="ts">
export default {
  name: 'footer',
}
</script>

<style lang="scss">
  .footer{
    width: 100%;
    background-color: #5E6B4F9E;
    height: 100px;
    align-items: center;
    .footerContainer{
        width: 90%;
        height: 100%;
        margin: auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
        .logoFooter{
            width: 150px;
        }
        .footerNav{
            display: flex;
            justify-content: space-around;
            width: 800px;
            align-items: center;
            height: 100%;
            a{
                text-decoration: underline;
                font: normal normal normal 18px TradeGothicLTPro;
                color: #FFFFFF;
            }
            p{
                font: normal normal normal 14px TradeGothicLTPro;
                color: #FFFFFF;
            }
            .separateur{
                width: 0;
                height: 16px;
                border: solid white 1px;
            }
            img{
                width: 20px;
                height: 20px;
            }
        }

    }
  }
</style>