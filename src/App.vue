<template>
  <div class="main-container">
    <Header />

    <div class="fullscreen">
      <router-view />
    </div>
  </div>
</template>

<script setup>
import Header from "./components/Header.vue";
</script>

<style>
#app {
  font-family: "Poppins", sans-serif;
  color: #2c3e50;
}
.main-container {
  height: 100vh;
  overflow: hidden;
}
.fullscreen {
  height: 100vh;
  overflow: scroll;
}
</style>
