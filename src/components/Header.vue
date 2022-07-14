<script setup>
import { reactive } from "vue";
const state = reactive({
  menuIsVisible: false,
});
</script>
<template>
  <header>
    <div class="mobile-view">
      <div class="logo">
        <img src="../assets/logo.png" alt="quest-realty-logo" />
      </div>
      <button @click="state.menuIsVisible = !state.menuIsVisible" class="menu">
        <img src="../assets/hamburger.png" alt="" />
      </button>
      <div class="dropdown" v-if="state.menuIsVisible">
        <router-link to="/">Home</router-link>
        <router-link to="/about">About</router-link>
        <router-link to="/for-sale">For Sale</router-link>
        <router-link to="for-rent">For rent</router-link>
        <router-link to="/login">Login</router-link>
        <router-link to="/register">Register</router-link>
      </div>
    </div>
    <div class="larger-view">
      <div class="logo">
        <img src="../assets/logo.png" alt="quest-realty-logo" />
      </div>
      <div class="nav">
        <router-link to="/" class="large-screen-nav">Home</router-link>
        <router-link to="/about" class="large-screen-nav">About</router-link>
        <router-link to="/for-sale" class="large-screen-nav"
          >For Sale</router-link
        >
        <router-link to="for-rent" class="large-screen-nav"
          >For rent</router-link
        >
      </div>
      <div class="auth">
        <router-link to="/login" class="large-screen-nav login"
          >Login</router-link
        >
        <router-link to="/register" class="large-screen-nav register"
          >Register</router-link
        >
      </div>
    </div>
  </header>
</template>

<style scoped>
header {
  box-shadow: 1px 1px 10px rgba(0, 0, 0, 0.61);
  position: sticky;
  top: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 0px 12px;
}
.logo {
  padding: 1rem 0;
}
.logo img {
  width: 76px;
  height: 56px;
}
.mobile-view {
  position: relative;
  width: 100%;
  padding: 0 4px;
  display: flex;
  align-items: center;
  justify-content: start;
}

.menu {
  width: fit-content;
  margin-left: auto;
  padding: 4px 6px;
  outline: none;
  border-radius: 4px;
  border: 1px solid rgba(212, 212, 212, 0.842);
}
.dropdown {
  display: flex;
  flex-direction: column;
  align-items: center;
  position: absolute;
  width: 200px;
  bottom: -190px;
  right: 10px;
  border: 1px solid rgba(212, 212, 212, 0.842);
  animation-name: menu;
  animation-duration: 1s;
}

@keyframes menu {
  from {
    opacity: 0;
    bottom: -150px;
  }
  to {
    opacity: 1;
    bottom: -190px;
  }
}

a {
  text-decoration: none;
  color: var(--barley-40);
}

.dropdown > a {
  width: 100%;
  text-align: center;
  border-bottom: 1px solid rgba(212, 212, 212, 0.842);
  padding: 4px 0;
}
.dropdown > a:hover {
  background-color: var(--barley-40);
  color: white;
}

.dropdown .router-link-exact-active {
  background-color: var(--barley-40);
  color: white;
}
.larger-view {
  display: none;
}
.auth .login {
  background-color: var(--barley-40);
  color: white;
  border-radius: 4px;
}

.auth .register {
  border-radius: 4px;
  border: 1px solid #6d553e;
}

@media (min-width: 786px) {
  .mobile-view {
    display: none;
  }

  .larger-view {
    display: flex;
    justify-content: space-between;

    align-items: center;
    width: 100%;
  }

  .large-screen-nav {
    padding: 10px 20px;
    margin: 0 4px;
  }

  .large-screen-nav.router-link-exact-active {
    border-bottom: 2px solid #6d553e;
  }
}
</style>
