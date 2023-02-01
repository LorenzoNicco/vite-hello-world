<script>
import AppTitle from  "./components/AppTitle.vue"
import AppHero from "./components/AppHero.vue";

export default {
  components: {
    AppTitle,
    AppHero
  },
  data() {
    return {
      count: 0
    }
  }
}
</script>

<template>
  <div class="background">
    <AppTitle/>

    <!-- <button @click="count++">Count is: {{ count }}</button> -->

    <AppHero/>
  </div>
</template>

<style scoped>
.background {
  width: 100vw;
  height: 100vh;
  background-color: cornflowerblue;
}

button {
  font-weight: bold;
  margin-top: 2rem;
}
</style>
