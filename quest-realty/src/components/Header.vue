<script setup>
import { ref } from 'vue';

defineProps({
  msg: String
})

const count = ref(0)
</script>
<template>
<div class="header">
  <header>
    <div class="logo">
  <img src="../assets/logo.png" alt="quest-realty-logo"/>
  </div>
  <div class="nav">
  <ul  class="nav-link">
    <li>Home</li>
     <li>About</li>
      <li>For Sale</li>
            <li>For Rent</li>

    
  </ul>
  <ul class="nav-button">
    <li><button class="login">Login</button></li>
    <li><button class="register">Register</button></li>

  </ul>
</div>
</header> 

</div>
</template>

<style scoped>
.header{
  width: 100%;
  left: 145px;
  display: flex;
  justify-content: space-around;
  align-items: center;

}
header {
height: 76px;
width: 950px;
display: flex;
justify-content: space-between;
align-items: center;
}
.logo{
  padding: 1rem 0;
  
}
.logo img{
  width: 76px;
  height: 56px;
}
.nav{
  display: flex;
  justify-content: space-between;
  align-items: center;
line-height: 3;
width: 900px;


}
.nav-link{
color:var(--barley-40);
margin: 0 1rem;

}
.nav-button{
display: flex;
justify-content: flex-end;
line-height: 2;
}
.nav-link, .nav-button{
  display: flex;
}.nav-link li {
  margin:0 1rem;
  font-size: 1.6rem;
  font-weight: 500;
  height:40px;
  color: var(--barley-40);
  padding: 0  1rem;

}


.nav-button li{
  margin:0 1rem;
}
button{
height:30px;
left:1164px;
border-radius:5px;
font-size: 1.6rem;
font-weight: 500;
outline:none;
}
.login{
  width: 80px;
  background-color: var(--barley-40);
  box-shadow: 0px 4px 4px 0px #00000024;
color:var(--white);
}
.register{
  width: 100px;
  background-color:#fff;
  color: var(--barley-40);
    box-shadow: 0px 4px 4px 0px #00000024;

}
.home-container{
  width: 100%;
  background-color: red;
  height: 700px;
  display: flex;
  position: absolute;
}</style>