<template>
  <nav class="nav">
    <img src="images/comme-au-marche.png" alt="logo" class="logoNav">
        <svg class="Ellipse_1" xmlns="http://www.w3.org/2000/svg" width="1000" height="1000" viewBox="0 0 1288 1288">
      <circle id="Ellipse_1" data-name="Ellipse 1" cx="644" cy="644" r="644" fill="#c99466" opacity="0.596"/>
    </svg>
    <img src="images/compte.png" alt="pictoConnect" class="pictoCompte">
    <img src="images/sac.png" alt="sac" class="sac">
  </nav>
</template>

<script lang="ts">
export default {
  name: 'Nav',
}
</script>

<style lang="scss">
  .nav{
    width: 90%;
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 10px;
    position: relative;
    .pictoCompte{
      width: 30px;
      z-index: 1;
    }
    .Ellipse_1{
      position: absolute;
      top: 0px;
      right: 0px;
      transform: translate(50%, -50%);
      z-index: -1;
    }
    .logoNav{
      height: 100px;

    }
    .sac{
      position: absolute;
      top: 170px;
      right: 180px;
      width: 250px;
    }
  }
  @media screen and (max-width: 1024px){
    .nav{
      .logoNav{
        height: 80px;
      }
      svg{
        width: 100%;
      }
      .sac{
        display: none;
      }
    }
}
</style>