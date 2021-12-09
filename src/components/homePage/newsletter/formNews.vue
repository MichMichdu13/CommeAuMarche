<template>
    <div class="formNews">
        <form action="" method="post" class="formulaireNews">
            <div class="newsInput">
                <input type="email" name="newsInput" id="newsInput" placeholder="E-mail" required>
            </div>
            <div class="button2">
                <button type="submit">S’abonner</button>
            </div>
        </form>
    </div>
</template>

<script lang="ts">

export default {
  name: 'formNews',
    components: {
  },
}
</script>

<style lang="scss">
    .formNews{
    display: flex;
    justify-content: center;
    margin: 100px;
    .formulaireNews{
        display: flex;
        flex-wrap: nowrap;
        input{
            border: 1px solid #3C5424;
            border-radius: 10px;
            padding-left: 10px;
            &::placeholder{
                color: #5E6B4F;
                opacity: 0.49;
                font-family:"TradeGothicLTPro";  
                font-size: 20px;
            }
        }
        .newsInput{
            grid-area: what;
            #newsInput{
                width: 310px;
                height: 50px;

            }
        }
        .button2{
            grid-area: button2;
            button{
                width: 100px;
                height: 54px;
                background: #5E6B4F;
                border: none;
                border-radius: 10px;
                opacity: 0.62;
                display: flex;
                justify-content: center;
                align-items: center;
                color: white;
                font: normal normal normal 18px TradeGothicLTPro;
                margin-left: 15px;

            }
        }
    }

}

</style>