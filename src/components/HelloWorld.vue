<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="text">{{ msg }}</h1>
    <h3>
      You’ve successfully created a project with
      <a target="_blank" href="https://vitejs.dev/">Vite</a> +
      <a target="_blank" href="https://v3.vuejs.org/">Vue 3</a>.
    </h3>
  </div>
</template>

<style scoped lang="scss">
@import 'bootstrap/scss/bootstrap';
.text {
@extend .text-danger;
@extend .text-center;
}
</style>
