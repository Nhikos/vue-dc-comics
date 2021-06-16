<template>
  <div class="card">
      <div class="img_container">
          <img :src="item" alt="">
      </div>
          <h2>{{ title }}</h2>
  </div>
</template>

<script>
export default {
    name: "Card",
    props: ["item" , "title"]
}
</script>

<style lang = "scss" scoped>
    .card {
        width: calc(100% / 6 - 2%);
        height: 338px;
        margin: 30px 1%;

        .img_container {
            height: 100%;
            overflow: hidden;
        }

        img {
            height: 100%;
            width: 100%;
            object-fit: cover;
            object-position: top;
            cursor: pointer;
        }
    }

    h2 {
        color: white;
        font-size: 14px;
        margin-top: 10px;
        text-transform: uppercase;
        cursor: pointer;
    }

</style>