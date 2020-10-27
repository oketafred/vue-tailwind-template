<template>
  <div class="text-center align-middle">
    <img class="mx-auto" alt="Vue logo" src="./assets/logo.png" />
    <h1 class="text-4xl font-semibold">Tailwind CSS and Vue JS Version 3</h1>
    <HelloWorld msg="Welcome to Your Vue.js and Tailwind App" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>

<style src="./assets/tailwind.css"/>
