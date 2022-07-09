<script setup>

</script>

<template>
<div class="home-container">
  <div class="home-main">
  <div class="left">
    <h3>Find Your Next Perfect Place To Live.</h3>
    <p>There is no better feeling than walking through the door to your new house and knowing you are fully home at Quest Realty we make this dream a happy reality. </p>
    <button>Learn more</button>
    </div>
  <div class="right">
    
    </div>
</div> 
<div class="home-footer">
  <div></div>
</div>
</div>
</template>

<style scoped>
.home-container{
  font-family: inherit;
width: 1150px;
   position: absolute;
left: 165px;
top: 180px;
display: flex;
flex-direction: column;

}
.home-main{
  display: flex;
justify-content: space-between;
align-items: center;
}

.left{
  width: 400px;
    height: 394px;


}
.left >h3{
font-size: 3rem;
font-weight: 700;
line-height: 3.5rem;
height: 124px;
color:var(--barley-40);
width: 300px;



}
.left> p{
font-size: 1.1rem;
line-height: 1.5rem;
height: 84px;
color:var(--oslo-gray);
width: 265px;



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
  width: 700px;
  border: 1px solid black;
  height: 394px;
}
.home-footer{
 width:800px;
height:100px;
border: 1px solid black;
border-radius: 8px;
top:910px;
left: 198px;


}
</style>