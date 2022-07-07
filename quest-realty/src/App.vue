<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from "./components/HelloWorld.vue";
import Agents from "./components/Agents.vue";
</script>

<template>
  <div>
    <Agents></Agents>
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: "Poppins", sans-serif;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
