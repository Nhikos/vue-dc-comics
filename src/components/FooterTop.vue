<template>
  <div class="footer_top">
      <div class="wrapper">
          <div class="container">
              <div class="first_column">
                  <h3>DC COMICS</h3>
                  <ul>
                      <li>Characters</li>
                      <li>Movies</li>
                      <li>TV</li>
                      <li>Games</li>
                      <li>Videos</li>
                      <li>News</li>
                  </ul>
                  <h3>SHOP</h3>
                  <ul>
                      <li>Shop DC</li>
                      <li>Shop DC Collectibles</li>
                  </ul>
              </div>
              <div class="second_column">
                  <h3>DC</h3>
                  <ul>
                      <li>Terms Of Use</li>
                      <li>Privacy policy(New)</li>
                      <li>Ad Choices</li>
                      <li>Advertising</li>
                      <li>Subscriptions</li>
                      <li>Talent Workshops</li>
                      <li>CPSC Certificates</li>
                      <li>Ratings</li>
                      <li>Shop Help</li>
                      <li>Contact Us</li>
                  </ul>
              </div>
              <div class="third_column">
                  <h3>SITES</h3>
                  <ul>
                      <li>DC</li>
                      <li>MAD Magazine</li>
                      <li>DC Kids</li>
                      <li>DC Universe</li>
                      <li>DC Power Visa</li>
                  </ul>
              </div>
          </div>
      </div>
  </div>
</template>

<script>

export default {
  name: 'FooterTop',
}
</script>

<style lang="scss" scoped>

    .footer_top {
        width: 100%;
        background-image: url(../assets/img/footer-bg.jpg);
    }

    .wrapper {
        display: flex;
        justify-content: flex-start;
        align-items: center;
        height: 270px;
        width: 70%;
        margin: auto;
        background-image: url(../assets/img/dc-logo-bg.png);
        background-repeat: no-repeat;
        background-position: right;
        background-size: 408px;
    }

    h2 {
        color: white;
    }

    h3 {
        color: white;
        margin: 8px 0;
    }

    .container {
        display: flex;
    }

    li {
        list-style: none;
        color: grey;
        font-size: 10px;
        padding: 2px;
        margin-right: 50px;
        cursor: pointer;
    }

    li:hover {
        color: #0282f9;
        cursor: pointer;
    }
</style>