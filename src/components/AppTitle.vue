<script>
export default {
  data() {
    return {
      message: "La mia prima app con Vite!"
    }
  }
}
</script>

<template>
  <h1>{{ message }}</h1>
</template>

<style scoped>
    h1 {
        color: floralwhite;
        position: absolute;
        top: 10%;
        left: 50%;
        transform: translateX(-50%);
    }
</style>
