<script setup>
import Reason from './Reason.vue';

</script>

<template>
<div class="home-container">
  <div class="home-main">
  <div class="left">
    <h2>Find Your Next Perfect Place To Live.</h2>
    <p>There is no better feeling than walking through the door to your new house and knowing you are fully home at Quest Realty we make this dream a happy reality. </p>
    <button>Learn more</button>
    </div>
  <div class="right">
    <img class="frame-one" src="../assets/Frame 290.jpg" alt="quest-realty"/>
    </div>
</div> 
<div class="home-footer">
  <div class="icons">
<div>
  <div class="svg">
  <svg width="18" height="18" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
<path class="fill" d="M20.6211 8.45C19.5711 3.83 15.5411 1.75 12.0011 1.75C12.0011 1.75 12.0011 1.75 11.9911 1.75C8.46107 1.75 4.42107 3.82 3.37107 8.44C2.20107 13.6 5.36107 17.97 8.22107 20.72C9.28107 21.74 10.6411 22.25 12.0011 22.25C13.3611 22.25 14.7211 21.74 15.7711 20.72C18.6311 17.97 21.7911 13.61 20.6211 8.45ZM12.0011 13.46C10.2611 13.46 8.85107 12.05 8.85107 10.31C8.85107 8.57 10.2611 7.16 12.0011 7.16C13.7411 7.16 15.1511 8.57 15.1511 10.31C15.1511 12.05 13.7411 13.46 12.0011 13.46Z" fill="#292D32"/>
</svg>
<h3>Location</h3>
</div>
<div class="dropdown">
<p>Choose State</p>
<svg width="16" height="16" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M17.9188 8.17969H11.6888H6.07877C5.11877 8.17969 4.63877 9.33969 5.31877 10.0197L10.4988 15.1997C11.3288 16.0297 12.6788 16.0297 13.5088 15.1997L15.4788 13.2297L18.6888 10.0197C19.3588 9.33969 18.8788 8.17969 17.9188 8.17969Z" fill="#292D32"/>
</svg>

</div>
</div>
<div class="icon">
<div class="svg">
  <svg width="18" height="18" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
<path class="fill" d="M22 21.2488H21V9.97875C21 9.35875 20.72 8.77875 20.23 8.39875L19 7.43875L18.98 4.98875C18.98 4.43875 18.53 3.99875 17.98 3.99875H14.57L13.23 2.95875C12.51 2.38875 11.49 2.38875 10.77 2.95875L3.77 8.39875C3.28 8.77875 3 9.35875 3 9.96875L2.95 21.2488H2C1.59 21.2488 1.25 21.5888 1.25 21.9988C1.25 22.4088 1.59 22.7488 2 22.7488H22C22.41 22.7488 22.75 22.4088 22.75 21.9988C22.75 21.5888 22.41 21.2488 22 21.2488ZM6.5 12.7487V11.2487C6.5 10.6987 6.95 10.2487 7.5 10.2487H9.5C10.05 10.2487 10.5 10.6987 10.5 11.2487V12.7487C10.5 13.2987 10.05 13.7487 9.5 13.7487H7.5C6.95 13.7487 6.5 13.2987 6.5 12.7487ZM14.5 21.2488H9.5V18.4987C9.5 17.6687 10.17 16.9987 11 16.9987H13C13.83 16.9987 14.5 17.6687 14.5 18.4987V21.2488ZM17.5 12.7487C17.5 13.2987 17.05 13.7487 16.5 13.7487H14.5C13.95 13.7487 13.5 13.2987 13.5 12.7487V11.2487C13.5 10.6987 13.95 10.2487 14.5 10.2487H16.5C17.05 10.2487 17.5 10.6987 17.5 11.2487V12.7487Z" fill="#292D32"/>
</svg>
<h3>Property Type</h3>
</div>
<div class="dropdown">
<p>Choose Property</p>
<svg width="16" height="16" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M17.9188 8.17969H11.6888H6.07877C5.11877 8.17969 4.63877 9.33969 5.31877 10.0197L10.4988 15.1997C11.3288 16.0297 12.6788 16.0297 13.5088 15.1997L15.4788 13.2297L18.6888 10.0197C19.3588 9.33969 18.8788 8.17969 17.9188 8.17969Z" fill="#292D32"/>
</svg>
</div>
</div>
<div class="icon">
  <div class="svg">
 <svg width="18" height="18" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
<path class="fill" d="M19.1709 6.63953C18.7409 4.46953 17.1309 3.51953 14.8909 3.51953H6.11094C3.47094 3.51953 1.71094 4.83953 1.71094 7.91953V13.0695C1.71094 15.2895 2.62094 16.5895 4.12094 17.1495C4.34094 17.2295 4.58094 17.2995 4.83094 17.3395C5.23094 17.4295 5.66094 17.4695 6.11094 17.4695H14.9009C17.5409 17.4695 19.3009 16.1495 19.3009 13.0695V7.91953C19.3009 7.44953 19.2609 7.02953 19.1709 6.63953ZM5.53094 11.9995C5.53094 12.4095 5.19094 12.7495 4.78094 12.7495C4.37094 12.7495 4.03094 12.4095 4.03094 11.9995V8.99953C4.03094 8.58953 4.37094 8.24953 4.78094 8.24953C5.19094 8.24953 5.53094 8.58953 5.53094 8.99953V11.9995ZM10.5009 13.1395C9.04094 13.1395 7.86094 11.9595 7.86094 10.4995C7.86094 9.03953 9.04094 7.85953 10.5009 7.85953C11.9609 7.85953 13.1409 9.03953 13.1409 10.4995C13.1409 11.9595 11.9609 13.1395 10.5009 13.1395ZM16.9609 11.9995C16.9609 12.4095 16.6209 12.7495 16.2109 12.7495C15.8009 12.7495 15.4609 12.4095 15.4609 11.9995V8.99953C15.4609 8.58953 15.8009 8.24953 16.2109 8.24953C16.6209 8.24953 16.9609 8.58953 16.9609 8.99953V11.9995Z" fill="#292D32"/>
<path d="M22.3017 10.9183V16.0683C22.3017 19.1483 20.5417 20.4783 17.8917 20.4783H9.11172C8.36172 20.4783 7.69172 20.3683 7.11172 20.1483C6.64172 19.9783 6.23172 19.7283 5.90172 19.4083C5.72172 19.2383 5.86172 18.9683 6.11172 18.9683H14.8917C18.5917 18.9683 20.7917 16.7683 20.7917 13.0783V7.91832C20.7917 7.67832 21.0617 7.52832 21.2317 7.70832C21.9117 8.42832 22.3017 9.47832 22.3017 10.9183Z" fill="#292D32"/>
</svg>
<h3>Price Range</h3>
</div>
<div class="dropdown">
<p>Choose Price</p>
<svg width="16" height="16" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M17.9188 8.17969H11.6888H6.07877C5.11877 8.17969 4.63877 9.33969 5.31877 10.0197L10.4988 15.1997C11.3288 16.0297 12.6788 16.0297 13.5088 15.1997L15.4788 13.2297L18.6888 10.0197C19.3588 9.33969 18.8788 8.17969 17.9188 8.17969Z" fill="#292D32"/>
</svg>

</div>
</div>
<button>Search</button>
</div>
</div>

</div>

</template>

<style scoped>
.home-container{
  font-family: inherit;
width: 950px;
height:700px;
display: flex;
flex-direction: column;
background-color:#fff;

}
.home-main{
  display: flex;
justify-content: space-between;
align-items: center;
}

.left{
  position: absolute;
  left: 275px;

top: 176px;
    height: 350px;



}
.left >h2{
font-size: 2.6rem;
font-weight: 700;
line-height: 3.5rem;
height: 124px;
color:var(--barley-40);
width: 245px;
font-family: inherit;



}
.left> p{
font-size: 1rem;
line-height: 1.6rem;
height: 104px;
color:var(--oslo-gray);
width: 235px;



}

.left >button{
  height: 35px;
width: 106px;
border-radius: 5px;
color:var(--white);
padding:0 1rem;
outline: none;
border:2px solid var(--barley-40);
  background-color:var(--barley-40);
font-size: 1.4rem;
  box-shadow: 0px 4px 4px 0px #00000024;


}
.left button:hover{
  transition: all 300ms ease;
}
.right{
top: 156px;
  left: 675px;
  width: 700px;
  height: 350px;
  position: absolute;
}
.right .frame-one{
width:80%;
height: 100%;
}
.home-footer{
 width:800px;
height:60px;
border-radius: 8px;
position: absolute;
top:550px;
left: 298px;
box-shadow: 0px 10px 20px 0px #0000004D;
padding: 1rem .5rem;




}
.icons{
  display: flex;
  justify-content: space-between;
  align-items: center;
}
 .icon{
width:150px;

}

.icons h3{
  padding: .3rem ;
  font-size: 1.25rem;
}
.dropdown p{
  font-size: 1rem;
  padding-left: .2rem;
  background-color: #fff;  
}

 .svg{
  display: flex;
  justify-content: center;
  align-items: center;
  padding:0 1rem;

}
svg{
    margin: 0 1rem;
}
 .fill{
fill: #352A1F;

}
.dropdown{
  padding: .25rem 0 ;
  display: flex;
  justify-content: center;
  align-items: center;
}
.icons > button{
   height: 35px;
width: 80px;
border-radius: 5px;
color:var(--white);
padding:0 1rem;
margin: 0 1rem;
outline: none;
border:2px solid var(--barley-40);
  background-color:var(--barley-40);
font-size: 1.4rem;
  box-shadow: 0px 4px 4px 0px #00000024;

}
</style>