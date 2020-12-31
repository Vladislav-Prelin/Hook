<template>
    <div class="section_basement">
                <div class="section_basement_left">
                    <h1 class="section_basement_text_header">Связаться с нами</h1>
                    <div class="section_basement_form">
                        <form class="form">
                        <h1 class="section_basement_text">Ваше имя</h1>
                        <input type="text" name="mfbName" placeholder="Your name" required/>
                        <h1 class="section_basement_text">Ваш телефон</h1>
                        <input type="text" name="mfbMail" placeholder="Your phone name" required/>
                        <h1 class="section_basement_text">Сообщение</h1>
                        <textarea class="input_form" type="text" name="massage" placeholder="Your massage" required/>
                        <input type="submit" value="Отправить" />
                        </form>
                    </div>
                </div>
                <div class="section_basement_right">
                    <div class="section_basement_rigth_block">
                        <div class="section_basement_right_text">Подготовтесь до быстрого ответа</div>
                    <a class="section_basement_right_link" href="">shotsebrand@gmail.com</a>
                    <p2 class="section_basement_rigth_city">Киев</p2>
                    <p class="section_basement_right_phone_one">+38 073-420-22-41</p>
                    <p class="section_basement_right_phone_text">Позвоните нам</p>
                    <p class="section_basement_right_phone_two">+38 063-371-07-18</p>
                        <ul class="section_basement_right_profile">
                            <li class="section_basement_right_sidebar">
                                <img src="../img/one.jpg" class="section_basement_right_img" alt="">
                            </li>
                            <li class="section_basement_right_sidebar_one">
                                <img src="../img/one.jpg" class="section_basement_right_img_one" alt="">
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
</template>
<script>
export default {
}
</script>



<style>

.section_basement {
    overflow: hidden;
    display: flex;
    height: 100vh;
    min-height: 1000px;
    width: 100%;
}



.section_basement {
}


.section_basement_left {
    width: 79%;
}

.section_basement_left {
    background-image: url('../img/link1.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    overflow: hidden;
}

.section_basement_form {
    min-height: 100vh;
    display: flex;
    justify-content: center;
    margin-top: 14.9rem;
    /* align-items: center;
    margin:  0 auto; */


}



.form{
    max-width: 400px;


}
input, textarea{
    max-width: 21rem;
    max-height: 120px;
    min-height: 4rem;
    font-size: 24px;
    box-sizing: border-box;
    display: block;
    border: none;
    /* box-shadow: inset 0px 0px 0px 1px rgba(0, 0, 0, 0.11); */
    padding: 20px 20px;
    border-radius: 2rem;
    overflow: hidden;
    margin: 15px 0;
    outline: none;
}
input[type="submit"]{
    background: red;
    border: none;
    box-shadow: 0px 2px 0 1px #C50909;
    border-radius: 2rem;
    padding: 15px 15px;
    color: white;
    text-transform: uppercase;
    font-weight: 600;
    /* width: 200px; */
    cursor: pointer;
    transition: 0.3s;
}
input[type="submit"]:hover{
    background: black;
    box-shadow: 0px 2px 0 1px black;
}

.section_basement_text {
    font-size: 20px;
    font-family: 'Cacefont', sans-serif;
}

.section_basement_text_header {
    display: flex;
    font-size: 60px;
    padding-top: 7rem;
    padding-left: 7rem;
    position: absolute;
    font-family: 'Conv_link';
}


.section_basement_right {
    width: 21%;
    background-color:#000;
}


.section_basement_rigth_block  {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding-left: 12.5%;

}

.section_basement_right_text {
    color: #fff;
    display: flex;
    /* justify-content: flex-start;
    align-items: center;
    text-align: center; */
    padding-top: 15rem;
    font-size: 22px;
    /* font-family: 'Cacefont', sans-serif; */

}

.section_basement_right_link {
    display: flex;
    margin-top: 1rem;
    font-size: 20px;
    font-weight: 900;
    font-family: 'Cacefont', sans-serif;
    color: red;


}

.section_basement_rigth_city {
    display: flex;
    color: #fff;
    font-size: 22px;
    padding-top: 5rem;

}

.section_basement_right_phone_one {
    color: #fff;
    display: flex;
    justify-content: center;
    padding-top: 1rem;
    font-size: 20px;
    font-family: 'Cacefont', sans-serif;
 
}

.section_basement_right_phone_text{
    display: flex;
    font-size: 21px;
    color: #fff;
    padding-top: 1rem;
    /* font-family: 'Cacefont', sans-serif; */

}

.section_basement_right_phone_two {
    display: flex;
    font-size: 20px;
    color: #fff;
    padding-top: 1rem;
    justify-content: center;
    font-family: 'Cacefont', sans-serif;


}

.section_basement_right_img {
    display: flex;
    margin-top: 7rem;
    border-radius: 50%;
    justify-content: left;
    width: 60px;
    height: 60px;

}

.section_basement_right_img_one {
    display: flex;
    margin-top: 2rem;
    border-radius: 50%;
    justify-content: left;
    width: 60px;
    height: 60px;
}

.section_basement_right_icon {
    color: #fff;
}

</style>