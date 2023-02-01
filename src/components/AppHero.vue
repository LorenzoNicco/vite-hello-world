<script>
export default {
  data() {
    return {
      image: "../src/assets/img/marek-piwnicki-RsfF900AX2A-unsplash.jpg"
    }
  }
}
</script>

<template>
  <div class="jumbotron">
    <img :src="image" alt="">
  </div>
</template>

<style scoped>
    .jumbotron {
        height: 100%;
    }

    img {
        height: 100%;
    }
</style>
