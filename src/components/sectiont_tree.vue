<template>
  <div class="section_look">
    <div class="section_look_block">
      <div class="section_look_wrap">
        <h1 class="section_look_text">We cannot shy away from what we want</h1>
      </div>
      <h1 class="section_look_text_vault">RODINA X</h1>
    </div>
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

.section_look {
  min-height: 1000px;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  background:#424242;
}

.section_look_block {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background:000;
  /* min-height: 900px; */
  height: 100vh;

}

.section_look_wrap {
  justify-content: center;
  padding: 23px 23px;
  box-shadow: 0 0 5px 2px red;
}

 .section_look_text {
   padding: 20px 20px;
   justify-content: center;
   align-items: center;
   text-align: center;
   /* min-height: 100%; */
   color: #fff;
  font-size: 65px;
  line-height: 60px;
}

.section_look_text_vault {
  width: 40rem;
  color: #fff;
  font-size: 60px;
  padding-top: 10rem;
  justify-content: center;
  align-items: center;
  text-align: center;

}
/* .left,.right {
  border: solid black;
  border-width: 0 3px 3px 0;
  display: inline-block;
  padding: 3px;
}

.left {
  padding-right: 2px;
  transform: rotate(135deg);

}
.right {
  transform: rotate(-45deg);
} */

</style>
