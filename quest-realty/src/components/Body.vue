<script setup>

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
    <img src="../assets/Frame 290.jpg" alt="quest-realty"/>
    </div>
</div> 
<div class="home-footer">
  <ul>
<li></li>
</ul>
</div>
</div>
</template>

<style scoped>
.home-container{
  font-family: inherit;
width: 950px;

display: flex;
flex-direction: column;

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
.right img{
width:80%;
height: 100%;
}
.home-footer{
 width:800px;
height:80px;
border: 1px solid black;
border-radius: 8px;
position: absolute;
top:550px;
left: 298px;
  box-shadow: 0px 4px 4px 0px #00000024;




}
</style>