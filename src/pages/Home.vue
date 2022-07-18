<script setup>
import FirstSection from "../components/home/first-section.vue";
import SecondSection from "../components/home/second-section.vue";
import OurServices from "../components/home/OurServices.vue";
import Agents from "../components/home/Agents.vue";
import FeaturedProperties from "../components/home/FeaturedProperties.vue";
import TopExecutives from "../components/home/TopExecutives.vue";

defineProps({
  msg: String,
});
</script>

<template>
  <div class="home">
    <FirstSection />
    <SecondSection />
    <OurServices />
    <Agents />
    <FeaturedProperties />
    <TopExecutives />
  </div>
</template>

<style scoped>
.home {
  width: 100%;
}
</style>
