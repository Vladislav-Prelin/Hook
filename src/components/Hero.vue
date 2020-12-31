<template>
    <div class="Header">

      <div class="hero_icon"> 
        </div>

      
    <header>
      <div class="navbar">
        <div class="logo">Shotse</div>
              <ul class="header_navbar">
                <li class="header_navbar_li"><a class="navbar_li">MASK</a></li>
                    <li class="header_navbar_li"><a class="navbar_li">PANTS</a></li>
                      <li class="header_navbar_li"><a class="navbar_li">GLASSES</a></li>
                        <li class="header_navbar_li"><a class="navbar_li">BADGE</a></li>
              </ul>
      </div>
    </header>

      <!-- <video class="hero-bg-video" width="400" height="300"  muted autoplay>
     <source src="../img/video.webm" type='video/mp4; codecs="avc1.42E01E, mp4a.40.2"'>
  </video> -->
    
<Item/>
    </div>
        
</template>

<script>
import Item from './item'
export default {
    components:{
        Item
    }
}
</script>

<style>

a{
text-decoration: none;
color: #fff;
}



.Header {
  width: 100%;
  min-height: 1000px;
  position: absolute;
}
.hero_icon{
  height: 100vh;
  width: 100%;
  top:0;
  left:0;
  z-index: 1;
  overflow: hidden;
  background-size:cover;
  background-image: url('../img/title_two_people.jpg');
}



   .navbar {
   z-index: 1111;
   position: fixed;
   height: 75px;
   width: 100%;
   left:0;
   right: 0;
   bottom: 0;
   top: 0;
   color:#fff;
   display: flex;   
   justify-content: space-between;

 }

.logo {
  font-family: 'Conv_Header',sans-serif;
  padding-top: 10px;
  font-size: 35px;
  line-height: 1.5;
  letter-spacing: 3px;
  font-weight: 500;
  padding-left: 2rem;
  background-color: #000;
}


.header_navbar {
  display: flex;
  justify-content: space-between;
  background-color: #000;
  padding: 25px 25px;
  flex-basis: 50%;
  width: 100px;
  height: 75px;
}

.header_navbar {
}
.header_navbar_li {
   font-family: 'Conv_header_navbar',sans-serif;
  font-size: 20px;
  display: flex;
  justify-content: center;
  text-align: center;
  align-items: center;
}

</style>