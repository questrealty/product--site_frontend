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
  display: flex;
  justify-content: space-around;
  align-items: center;

}
header {
width: 1150px;
height: 76px;
left: 145px;
top: 54px;
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
width: 1150px;
line-height: 2.9;


}
.nav-link{
color:var(--barley-40);
margin: 0 1rem;

}
.nav-button{
display: flex;
justify-content: flex-end;
}
.nav-link, .nav-button{
  display: flex;
}.nav-link li {
  margin:0 2rem;
  font-size: 1.5rem;
  height:30px;

}


.nav-button li{
  margin:0 1rem;
}
button{
  width:76px;
height:30px;
left:1164px;
border-radius:5px;
font-size: 1.6rem;
outline:none;
}
.login{
  background-color: var(--barley-40);
  box-shadow: 0px 4px 4px 0px #00000024;
color:var(--white);
}
.register{
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