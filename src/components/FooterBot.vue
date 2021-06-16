<template>
  <div class="footer_bot">
      <div class="wrapper">
          <div class="button"> SIGN-UP NOW!</div>
          <div class="section_right">
              <span>FOLLOW US</span>
              <img src="../assets/img/footer-facebook.png" alt="">
              <img src="../assets/img/footer-twitter.png" alt="">
              <img src="../assets/img/footer-periscope.png" alt="">
              <img src="../assets/img/footer-youtube.png" alt="">
              <img src="../assets/img/footer-pinterest.png" alt="">
          </div>
      </div>
  </div>
</template>

<script>

export default {
  name: 'FooterBot',
}
</script>

<style lang="scss" scoped>

    .footer_bot {
        width: 100%;
        background-color: #303030;
    }

    .wrapper {
        display: flex;
        justify-content: space-between;
        align-items: center;
        height: 100px;
        width: 70%;
        margin: auto;
    }

    .button {
        color: white;
        padding: 10px;
        border: 2px solid #0282f8;
        cursor: pointer;
    }

    .section_right {
        display: flex;
        justify-content: space-around;
        align-items: center;
    }

    img {
        margin-left: 10px;
        cursor: pointer;
    }

    span {
        color: #0282f8;
        margin-right: 5px;
        cursor: pointer;
    }

</style>