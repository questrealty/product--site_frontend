<script setup>
import { ref } from 'vue';

defineProps({
  msg: String
})

const count = ref(0)
</script>

<template>
<header>
  <img src="../assets/logo.png" alt="quest-realty-logo"/>
  <ul>
    <li>Home</li>
     <li>About</li>
      <li>For Sale</li>
            <li>For Rent</li>

    
  </ul>
  <div>
    <button>Login</button>
        <button>Register</button>

  </div>
</header> 
</template>

<style scoped>
a {
  color: #42b983;
}
</style>
