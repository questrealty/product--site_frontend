<script setup>
import Header from '../components/Header.vue';
import Body from "../components/Body.vue"

defineProps({
  msg: String
})

</script>

<template>
<div class="home">
<Header />
<Body />
</div>

</template>

<style scoped>
.home{
  width: 100%;
  min-height: 100vh;
  position: relative;
  background-color: #fff;


}
</style>
