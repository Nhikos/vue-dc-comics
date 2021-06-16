<template>
  <div class="header">
    <div class="wrapper">
      <div class="header_logo">
        <img src="../assets/img/dc-logo.png" alt="">
      </div>
      <div class="header_right">
        <ul>
          <li v-for="(link,index) in links" :key="index" >
            <a :href="link.href"> {{ link.text }} </a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
  data () {
    return {
      links: [
          {
            text: "characters",
            href: "link",
            active: false,
          },
          {
            text: "comics",
            href: "link",
            active: false,
          },
          {
            text: "movies",
            href: "link",
            active: false,
          },
          {
            text: "tv",
            href: "link",
            active: false,
          },
          {
            text: "games",
            href: "link",
            active: false,
          },
          {
            text: "collectibles",
            href: "link",
            active: false,
          },
          {
            text: "videos",
            href: "link",
            active: false,
          },
          {
            text: "fans",
            href: "link",
            active: false,
          },
          {
            text: "news",
            href: "link",
            active: false,
          },
          {
            text: "shop",
            href: "link",
            active: false,
          },
      ]
    }
  }
}
</script>

<style scoped lang="scss">

  .wrapper {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 100px;
    width: 70%;
    margin: auto
  }

  .header {
    height: 100px;
    width: 100%;
    background-color: white;
  }

  img {
    width: 80px;
    cursor: pointer;
  }

  li {
    display: inline;
    color: black;
    padding: 37px 12px;
    background-color: white;
    cursor: pointer;
  }

  a {
    color: #5d5465;
    font-weight: 700;
    text-decoration: none;
    text-transform: capitalize;
  }

  a:hover {
    color: #0282f9;
  }

  li:hover {
    border-bottom: 3px solid #0282f9;
  }

  li:nth-child(2) {
    color: #0282f9;
    border-bottom: 3px solid #0282f9;
  }
</style>
