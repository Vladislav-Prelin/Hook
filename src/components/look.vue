<template>
    <div class="section_tree_icon">
    <div class="section_tree_icon_left"></div>


    <div class="section_tree_icon_center">
       <div class="section_tree_icon_header">We do not chase after time because happiness loves us and time is happiness</div>
       <a class="section_tree_icon_btn" href="" >SHOTSE BREND</a> 
   
  </div>
    <div class="section_icon_right"></div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  components:{

  }
}
</script>

<style>
.section_tree_icon {
  min-height:1000px;
  height: 100vh;
  display: flex;
  width: 100%;
  overflow: hidden;
  
}

.section_tree_icon_header {
  justify-content: center;
  text-align: center;
  flex-direction: column;
  display: flex;
  font-size: 3rem;
  padding: 30px 30px;
  color: aliceblue;
  font-family: sans-serif;
  letter-spacing: 0.1px;
  font-weight: 900;
}

.section_tree_icon_center {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background:#000;
  width: 30%;
}


/* .section_tree_icon_text{
  color: #fff;
} */
.section_tree_icon_left {
  width: 35%;
  padding-left: 10rem;
}
.section_tree_icon_left {
  background-image: url('../img/section_tree_right.jpg');
  background-size: cover;
}


.section_icon_right {
 background-image: url('../img/pershe.jpg'); 
 background-size: cover;
}
.section_icon_right {
    width: 35%;
}

.section_tree_icon_btn {
  display: block;
  box-sizing: border-box;
  margin: 0 auto;
  padding: 8px;
  width: 80%;
  max-width: 200px;
  background: #fff; /* запасной цвет для старых браузеров */
  background: rgba(0, 0, 0, 0.5);
  border-radius: 8px;
  color: #fff;
  text-align: center;
  text-decoration: none;
  letter-spacing: 1px;
  transition: all 0.3s ease-out;
}

.section_tree_icon_btn:hover,
.section_tree_icon_btn:focus,
.section_tree_icon_btn:active {
  background: #fff;
  color: #000;
  transition: all 0.5s ease-in;
}
</style>