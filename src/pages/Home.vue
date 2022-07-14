<script setup>
import FirstSection from "../components/home/first-section.vue";
import SecondSection from "../components/home/second-section.vue";
import Agents from "../components/home/Agents.vue";
defineProps({
  msg: String,
});
</script>

<template>
  <div class="home">
    <FirstSection />
    <SecondSection />
    <Agents />
    <Body />
  </div>
</template>

<style scoped>
.home {
  width: 100%;
}
</style>
