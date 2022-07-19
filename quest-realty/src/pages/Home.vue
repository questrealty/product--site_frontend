<script setup>
import Header from '../components/Header.vue';
import Body from "../components/Body.vue";
import Reason from "../components/Reason.vue"
defineProps({
  msg: String
})

</script>

<template>
<div class="home">
<Header />
<Body />
<Reason />

</div>

</template>

<style scoped>
.home{
  width: 100%;
  min-height: 100vh;


}
</style>
