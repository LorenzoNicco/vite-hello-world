<script>
import AppTitle from  "./components/AppTitle.vue"

export default {
  components: {
    AppTitle
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

    <button @click="count++">Count is: {{ count }}</button>
  </div>
</template>

<style scoped>
.background {
  width: 100vw;
  height: 100vh;
  background-color: cornflowerblue;
  padding-top: 5rem;
}

button {
  font-weight: bold;
  margin-top: 2rem;
}
</style>
