<template>
  <div>
     <div class="blank"/>
     <div class="wrapper">
         <div class="img1"/>
         <h2 class="title1">Nuxt vue.js фреймворк для   анимаций</h2>
       <div class="img2"/>
         <h2 class="title2">Nuxt vue.js фреймворк для   анимаций</h2>
     </div>
     <div class="blank"/>
  </div>
</template>

<script>

// import {gsap} from 'gsap';
export default {
}
</script>

<style>


html {
  box-sizing: border-box;
  font-size: 100%;
}
 *,*:hover,*:after {
   box-sizing: inherit;
   margin: 0;
   padding: 0;
 }

body {
  width: 100%;
  overflow-x: hidden;
  font-size: 16px;
  color: #000;
}
.img1 {
   width: 60%;
   height: 0%;
   background-size: cover;
   background-repeat: no-repeat;
   background-image: url('../img/title.jpg');
 }


 .img2 {
   background-image: url('../img/title.jpg');
   width: 100%;
   height: 1000px;
   position: absolute;
   bottom: 0;
   /* left:50%; */
   text-align:center;
   background-size: cover;
   background-repeat: no-repeat;
   background-position: center bottom;
   /* transform: translate(-50%, 0); */
 }



 .blank {
   width: 100%;
   height: 100vh;

 }
 .wrapper {
   width:100%;
   height: 100vh;
   display: flex;
   position: relative;
   justify-content: center;
   align-items: flex-end;
   overflow: hidden;
   /* background: red; */
 }




 .title1 {
   position: absolute;
   top: 50%;
   left: 20%;
   font-size: 20px;
   transform: translate(-50%, -50%);
   opacity: 0;
   z-index: 1;
 }







 .title2 {
   transform-origin: center center;
   translate: translate(-50% -50%);
   text-align: center;
   position: absolute;
   line-height: 60px;
   top: 50%;
   opacity: 0;
   z-index: 2;
   left: 50%;
 }
</style>
