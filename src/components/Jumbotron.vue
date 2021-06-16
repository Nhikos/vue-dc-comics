<template>
  <div class="jumbotron">
      <div class="wrapper">
      </div>
  </div>
</template>

<script>

export default {
  name: 'Jumbotron',
}
</script>

<style lang="scss" scoped>

    .jumbotron {
        width: 100%;
        height: 400px;
        background-image: url(../assets/img/jumbotron.jpg);
        background-repeat: no-repeat;
        background-size: auto;
    }

    .wrapper {
        display: flex;
        justify-content: flex-start;
        align-items: center;
        height: 100px;
        width: 70%;
        margin: auto;
    }

    h2 {
        color: white;
    }

</style>