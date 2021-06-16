<template>
  <div class="comics">
        <div class="current-series">
            <h1>current series</h1>
        </div>
      <div class="wrap">
        <div class="container">
            <Card
                v-for="(card, index) in cardList"
                :key="index"
                :item = "card.thumb"
                :title = "card.series"
            />
            <div class="button">
                <h2>load more</h2>
            </div>
        </div>
      </div>
  </div>
</template>

<script>
import cardList from "../JSON/dc-comics.json";
import Card from "./Card";
export default {
    name: "Comics",
    components: {
        Card
    },

    data: function () {
        return {
            cardList
        };
    }
}
</script>


<style lang = "scss" scoped>
    .comics {
        height: 932px;
        background-color: #1c1c1c
    }

    .wrap {
        display: flex;
        justify-content: center;
    }

    .container {
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
        width: 80%;
        height: 880px;
    }
    
    .button {
        color: white;
        text-transform: uppercase;
        font-size: 12px;
        margin-top: 51px;
        padding: 5px 30px;
        background-color: #0282f9;
        cursor: pointer;
    }

    .current-series {
        color: white;
        text-transform: uppercase;
        font-size: 12px;
        padding: 5px 30px;
        background-color: #0282f9;
        cursor: pointer;
    }
    
</style>