<template>
    <div class="item">
        <div class="section_two_block">
            <div class="section_two_info_left">

            <div class="section_two_info_header">Wery a world  leading product innovation tiam</div>
            <div class="section_two_info_dec">Collaborating with ambitious companies to create  digital experiences used by billions everyday.</div>
            <div class="section_two_info_btn">Inforamcia</div>
            </div>
            
            <div class="section_two_right">

            </div>
        </div>
        <look/> 
        <SectionTree/>
        <SectinInfo/>
         <SectionBase/>
         <nuxt/>
    </div>
</template>
<script>
import nuxt from './nuxt'
import look from './look'
import SectionTree from './sectiont_tree'
import SectinInfo from './section_information'
import SectionBase from './section_basement'
export default {
    components:{
       SectionTree,
       look,
       SectinInfo,
       SectionBase,
       nuxt

    }
}
</script>

<style>


body {
    height: 100%;
    width: 100%;
    padding: 0;
    margin: 0;
}

.item {
    min-height: 1200px;
    /* transform: translateY(-14rem); */
    padding: 0;
    margin: 0;
}
.section_two_right {
    width: 50%;
} 

.section_two_block {    
    min-height: 1000px;
    height: 100vh;
    display: flex;
}

.section_two_info_left {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 50%;
    padding: 50px;
    background:rgb(255, 255, 255);
}

.section_two_info_header {
    overflow: hidden;
    font-size: 64px;
    font-weight: 700;
    letter-spacing: -.02em;
    line-height: 65px;
}

.section_two_info_btn {

  margin-top: 40px;
  display: inline-block;
  width: 200px;
  padding: 8px;
  color: rgb(0, 0, 0);
  border: 1px solid rgb(24, 18, 18);
  text-align: center;
  outline: none;
  text-decoration: none;
  font-weight: 900;
  font-size: 20px;
  padding: 20px 30px 15px 30px;
  border-radius: 9px;
  transition: background .5s ease-in-out;
}

.section_two_info_btn:hover
.section_two_info_btn:active {
    background: red;
}
.section_two_info_dec {
    overflow-y:hidden;
    border:none;
    margin-right: 30px;
    margin-top: 20px;
    font-size: 30px;
    line-height: 36px;
    letter-spacing: -.03em;
    font-weight: 700;
    
}


.section_two_right {
    background-image: url('../img/top.jpg');
    background-size: cover;
}
</style>