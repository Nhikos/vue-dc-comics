<template>
  <div class="banner">
      <div class="wrapper">
          <div class="action">
              <img src="../assets/img/buy-comics-digital-comics.png" alt="">
              <h4>DIGITAL COMICS</h4>
          </div>
          <div class="action">
              <img src="../assets/img/buy-comics-merchandise.png" alt="">
              <h4>DC MERCHANDISE</h4>
          </div>
          <div class="action">
              <img src="../assets/img/buy-comics-subscriptions.png" alt="">
              <h4>SUBSCRIPTION</h4>
          </div>
          <div class="action">
              <img src="../assets/img/buy-comics-shop-locator.png" alt="">
              <h4>COMIC SHOP LOCATOR</h4>
          </div>
          <div class="action">
              <img class="visa" src="../assets/img/buy-dc-power-visa.svg" alt="">
              <h4>DC POWER VISA</h4>
          </div>
      </div>
  </div>
</template>

<script>

export default {
  name: 'Banner',
}
</script>

<style lang="scss" scoped>

    .banner {
        color: white;
        width: 100%;
        background-color: #0282f9;
    }

    .wrapper {
        display: flex;
        justify-content: space-around;
        align-items: center;
        height: 120px;
        width: 70%;
        margin: auto;
    }

    h4 {
        color: white;
        margin-left: 10px;
        cursor: pointer;
    }

    .visa {
        display: inline;
        width: 58px;
        height: 35px;
        cursor: pointer;
    }

    img {
        height: 47px;
        display: inline;
        cursor: pointer;
    }

    .action {
        display: flex;
        justify-items: center;
        align-items: center;
    }

</style>