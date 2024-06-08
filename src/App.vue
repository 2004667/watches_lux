<script >
import HeaderWL from './components/HeaderWL.vue'
import AboutWL from './components/AboutWL.vue'
import RentWL from './components/RentWL.vue'
import StepsWL from './components/StepsWL.vue'
export default{
    components: {HeaderWL,AboutWL,RentWL,StepsWL}
}
</script>

<template>
 <div id=app>
<header>
   
      

     <div class="backgroundimg"><img src="./assets/imagesforweb/shapka.png" alt=""></div>
     <HeaderWL/>
    <div class="twoclock"><img src="./assets/imagesforweb/main_page_clocks.png" alt="" style="margin-top:100px; margin-left:1017px"></div>
</header>
<AboutWL/>

        
<main>
<div class="aboutimg2">
            <img src="./assets/imagesforweb/aboutwatch2.jpg" alt="" width="492px" height="421px">
        </div>
        <div class="aboutimg1">
            <img src="./assets/imagesforweb/aboutwatch1.jpg" alt="" width="463px" height="572px">
        </div>
<RentWL/>
 <div class="rentimg"><img src="./assets/imagesforweb/vitrini.png" alt=""></div>
 <StepsWL/>
 <div class="leftup"><img src="./assets/imagesforweb/leftup.png" alt="" width="605px" height="319px"></div>
 <div class="rightup"><img src="./assets/imagesforweb/rightup.png" alt="" width="605px" height="319px"></div>
</main>
<footer>
    
</footer>
</div>
</template>

<style scoped>
    /* *{
        background-image: url(./assets/imagesforweb/shapka.png)     ;
        background-size:1920px 871px ;
        background-repeat:no-repeat ;
    } */
    .backgroundimg{
       position: relative;
       z-index: 1;
       width: 100%;
       overflow: hidden;
    }
    .twoclock{
        position: absolute;
        top: 0;
        right: 0;
        z-index: 3;
        margin-right: 300px;
        margin-top: 75px;
    }
    .aboutimg1{
        width: 463px;
        height: 572px;
        position: absolute;
        z-index: 8;
        margin-top: 650px;
        margin-left: 463px;
    }
    .aboutimg2{
        position: absolute;
        margin-top: 1102px;
        margin-left: 299px;
        z-index: 7;
    } .rentimg{
        position: absolute;
        z-index: 2;
        margin-top: 1834px;
        margin-left: 970px;
        width: 610px;
        height: 440px;
    } .leftup{
        position: absolute;
        z-index: 10;
        margin-top:2869px ;
        margin-left: 340px;
    } .rightup{
        position: absolute;
        z-index: 10;
        margin-top:2869px ;
        margin-left: 977px;
    }
</style>
