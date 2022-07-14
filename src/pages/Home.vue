<script setup>
import FirstSection from "../components/home/first-section.vue";
defineProps({
  msg: String,
});
</script>

<template>
  <div class="home">
    <FirstSection />
    <Body />
  </div>
</template>

<style scoped>
.home {
  width: 100%;
}
</style>
