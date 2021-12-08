<template>
    <div class="recherche">
        <form action="" method="post" class="formRecherche">
            <div class="what">
                <input type="text" name="what" id="what" placeholder="Que cherchez-vous ?" required>
            </div>
            <div class="where">
                <input type="text" name="where" id="where" placeholder="Où ?" required>
            </div>
            <div class="button">
                <button type="submit"><img src="images/loupe.png" alt="recherche"></button>
            </div>
        </form>
    </div>
</template>

<script lang="ts">
export default {
  name: 'titreMain',
}
</script>

<style lang="scss">
.recherche{
    display: flex;
    justify-content: center;
    .formRecherche{
        display: grid;
         grid-template-columns: 320px 15px 220px 15px 50px;
         grid-template-rows: 60px ;
        grid-template-areas: "what . where . button";
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
        .what{
            grid-area: what;
            #what{
                width: 310px;
                height: 50px;

            }
        }
        .where{
            grid-area: where;
            #where{
                width: 210px;
                height: 50px;


            }
        }
        .button{
            grid-area: button;
            button{
                width: 54px;
                height: 54px;
                background: #5E6B4F;
                border: none;
                border-radius: 10px;
                opacity: 0.62;
                display: flex;
                justify-content: center;
                align-items: center;
                img{
                    width: 40px;
                    height: 40px;
                }

            }
        }
    }

}
 
</style>