<template>
    <div class="section_information">
        <h2 class="section_information_title">Секреты нашего успеха</h2>
        <div class="section_information_block">
        
            <div class="section_information_left">
                <div class="section_information_case">
                    <img src="../icon/checked_checkbox.png" alt="">
                    <div class="section_information_case_logo">
                        <ul>
                    <li class="section_information_left_succes_one">
                        <h1 class="section_information_item_1">Лучшее в мире <br> посвященое вам</h1>
                        <p class="section_information_text">Нашие клиенты всегда остаються довольные,  <br>  потому что мы знаем что им надо</p>
                        </li>
                </ul>   
                    </div>
                </div>

                <div class="section_information_case">
                    <img src="../icon/forward.jpg" alt="">
                    <div class="section_information_case_logo">
                        <ul>
                    <li class="section_information_left_succes_one">
                        <h1 class="section_information_item_1">Ориентируемся на <br> безпрецендентное </h1>
                        <p class="section_information_text">Мы искренне верим что ели вы сможете это <br> представить мы сможем создать.</p>
                        </li>
                </ul>   
                    </div>
                </div>
                
                
                <div class="section_information_case">
                    <img src="../icon/Tilda_Icons_40_IT_startup.svg">
                    <div class="section_information_case_logo">
                        <ul>

                             <li class="section_information_left_succes_one">
                        <h1 class="section_information_item_1">Глобальные перспективы <br> с глобальным мышлением</h1>
                        <p class="section_information_text">Наша команда приехала со всего мира, предлагая <br> разнообразные точки зрения и опыт.</p>
                        </li>
                </ul>   
                    </div>
                </div>
                
            </div>


            <div class="section_information_right">
                    <div class="section_information_case">
                    <img src="../icon/Мозг_right.jpg" alt="">
                    <div class="section_information_case_logo">
                        <ul>
                    <li class="section_information_left_succes_one">
                        <h1 class="section_information_item_1">Лучшее в мире <br> посвященое вам</h1>
                        <p class="section_information_text">Нашие клиенты всегда остаються довольные,  <br>  потому что мы знаем что им надо.</p>
                        </li>
                </ul>   
                    </div>
                </div>

                <div class="section_information_case">
                    <img src="../icon/Лампочка_right.jpg" alt="">
                    <div class="section_information_case_logo">
                        <ul>
                    <li class="section_information_left_succes_one">
                        <h1 class="section_information_item_1">Ориентируемся на <br> безпрецендентное </h1>
                        <p class="section_information_text">Мы искренне верим что ели вы сможете это <br> представить мы сможем создать.</p>
                        </li>
                </ul>   
                    </div>
                </div>
                
                
                <div class="section_information_case">
                    <img src="../icon/Папка.jpg" alt="">
                    <div class="section_information_case_logo">
                        <ul>

                             <li class="section_information_left_succes_one">
                        <h1 class="section_information_item_1">Глобальные перспективы <br> с глобальным мышлением</h1>
                        <p class="section_information_text">Наша команда приехала со всего мира, предлагая <br> разнообразные точки зрения и опыт.</p>
                        </li>
                </ul>   
                    </div>
                </div>
            </div>
        </div>
        
    </div>
</template>

<script>
export default {

}
</script>


<style>
.section_information {
    display: flex;
    width: 100%;
    min-height: 1000px;
    height: 100vh;
    background-color: rgb(255, 255, 255);
    /* justify-content: center; */
    flex-direction: column;
    /* align-items: center;
    text-align: center; */
}

.section_information_block {
    margin-top: 3rem;
    width: 100%;
    padding: 50px 50px;
    display: flex;
    justify-content: center;
    align-items: center;

}


.section_information_title {
    display: flex;
    margin-top: 8rem;
    margin-left: 4rem;
    letter-spacing: 5px;
    font-family:'Conv_Item', sans-serif;
    font-size: 3rem;
}
.section_information_left {
    width: 50%;
    overflow-y: hidden;
    


}

.section_information_text {
    padding-top: 10px;
    line-height: 1.2;
    font-size: 19px;
    font-family: 'Conv_text', sans-serif;
}

.section_information_left_succes {
  padding-top: 10px;
}


.section_information_case {
    display: flex;
    margin-top: 1rem;
    padding: 20px 20px;
 

}

.section_information_case_img {
    width: 100px;
    height: 100px;
}

img {
    height: 50px;
    width: 50px;
}

.section_information_icon_img {
    display: flex;
    flex-direction: column;
    padding-top: 20px;

}

.section_information_left_succes_one {
    display: flex;
    flex-direction: column;
    margin-left: 15px;
    line-height: 1;
}

.section_information_item_1 {
    overflow-y: hidden;
    line-height: 1.2;
    font-size: 30px;
    font-weight: 500;
    letter-spacing: 1px;
    font-family: 'Conv_Item', sans-serif;
 
}



.section_information_right {
    width: 50%;
}




</style>