<template>
  <main class="main">
    <div>
      <img class="zametka" src="../assets/zametka.png" alt="photo">
    </div>
    <div class="ramka">
      <p>Подкатегория 2</p>
      <div>
        <img src="../assets/ramka1.png" alt="photo">
        <p>Шерзод Асадов анонсировал события новой рабочей недели Президента <br><span>08.05.2021</span></p>
        
      </div>
    </div>

    <div class="ramka1">
      <p>Подкатегория 2</p>
      <div>
        <img src="../assets/ramka.png" alt="photo">
        <p>Шерзод Асадов анонсировал события новой рабочей недели Президента <br><span>08.05.2021</span></p>
      </div>
    </div>

    <div class="ramka2">
      <p class="ramka2-text">Подкатегория 2</p>

      <div>
        <img src="../assets/ramka3.png" alt="photo">
        <img src="../assets/ramka3-bg.png" class="ramka2-bg" alt="">
        <p>Шерзод Асадов анонсировал события новой рабочей недели Президента <br><span>08.05.2021</span></p>

      </div>

    </div>


    <div class="ramka3">

      <div>
        <img src="../assets/laptop-bg.png" class="laptop-bg" alt="photo">
        <img src="../assets/laptop.png" alt="photo">
        <img src="../assets/footer-laptop.png" class="laptop-footer" alt="photo">
        <img src="../assets/header-laptop.png" class="laptop-header" alt="photo">
      </div>
      <div class="subtract">
        <!-- <p>Подкатегория 2</p> -->
        <img src="../assets/Subtract.png" alt="photo">
        <p>Подкатегория 2</p>
        <p class="laptop-text">Шерзод Асадов анонсировал события новой рабочей недели Президента <br><span>08.05.2021</span></p>
      </div>


    </div>

    <div class="ramka4">
      <p>Подкатегория 2</p>
      <div>
        <img src="../assets/ramka.png" alt="photo">
        <p>Шерзод Асадов анонсировал события новой рабочей недели Президента <br><span>08.05.2021</span></p>
      </div>
    </div>

    <div class="ramka5">
      <img src="../assets/pngkey1.png" alt="photo">
    </div>

  </main>
</template>

<script>
export default {
 data() {
   return{
   }
 }
}
</script>

<style scoped>
.main{
  position: relative;
  background-image: url('../assets/header-background.png');
  background-size:  1300px 550px ;
  background-repeat: no-repeat;
  min-height: 690px;
  margin: 0 auto;
}
.zametka{
  position: absolute;
  top: 26%;
  left: 20%;
  width: 80px;
}
.ramka {
  position: absolute;
  display: block;
  width: 260px;
  left: 33%;
  top: 11%
}
.ramka div{
  display: flex;
  width: 420px;
  align-items: center;
}

.ramka div p{
  font-size: 11px;
  color: rgba(18, 18, 18, 0.8);
  font-weight: 600;
  line-height: 16px;
}
.ramka img{
  width: 220px;
  margin-left: -25px;
  margin-top: -10px;
}
.ramka p{
  margin: 0;
  color: rgba(18, 18, 18, 0.7);
  font-size: 12px;

}
.ramka1 {
  position: absolute;
  display: block;
  width: 235px;
  left: 18%;
  top: 42%
}
.ramka1 div{
  display: block;
  align-items: center;
}

.ramka1 div p{
  margin-top: -20px;
  font-size: 11px;
  color: rgba(18, 18, 18, 0.8);
  font-weight: 600;
}
.ramka1 img{
  width: 200px;
  margin-left: -25px;
  margin-top: -58px;
}
.ramka1 p{
  margin: 0;
  color: rgba(18, 18, 18, 0.7);
  font-size: 12px;
  padding-right: 50px ;
}
span{
  color: rgba(18, 18, 18, 0.8);
}

.ramka2 {
  position: absolute;
  display: block;
  width: 260px;
  right: 2%;
  top: 0%
}
.ramka2 div{
  display: block;
  align-items: center;
}

.ramka2 div p{
  margin-top: -20px;
  padding: 0;
  font-size: 10.5px;
  color: #121212;
  font-weight: 600;
  line-height: 16px;
  transform: rotate(6deg);
}
.ramka2 img{
  width: 250px;
  margin-left: 0px;
  margin-top: -10px;
}
.ramka2 .ramka2-text{
  position: absolute;
  margin: 0;
  color: rgba(18, 18, 18, 0.7);
  font-size: 11px;
  padding-right: 50px ;
  transform: rotate(6deg);
  top: 18.5%;
  right: 25%;
}
.ramka2 .ramka2-bg{
  position: absolute;
  right: 10.9%;
  top: 24%;
  width: 210px;
}
.ramka3{}

.ramka3 img {
  position: absolute;
  display: block;
  width: 377px;
  left: 34%;
  bottom: 23%;
}

.ramka3 .laptop-bg{
  width: 290px;
  bottom: 34%;
  left: 37.5%;
}

.ramka3 p{
  position: absolute;
  left: 38.5%;
  bottom: 58%;
  margin: 0;
  color: rgba(255, 255, 255, 0.6);
  font-size: 7px;
}
.subtract {
  display: flex;
  justify-content: center;
  align-items: center;
}
.subtract img{
  width: 130px;
  position: absolute;
  bottom: 44.95%;
  left: 39.1%;
}

.subtract .laptop-text{
  position: absolute;
  bottom: 47%;
  left: 43.2%;
  width: 130px;
  margin-left: 83px;
  font-size: 10px; 
  color: white;
  font-weight: 700;
  line-height: 12px;
}
.ramka3 .laptop-header{
  width: 280.15px;
  left: 37.8%;
  bottom: 60.3%;
}

.laptop-text span{
  color: rgba(255, 255, 255, 0.8);
  font-weight: 400;
}

.ramka3 .laptop-footer{
  position: fixed;
  width: 247.95px;
  left: 39.5%;
  bottom: 32%;
}

.ramka4 {
  position: absolute;
  display: block;
  width: 260px;
  right: 15%;
  bottom: 30%
}
.ramka4 div{
  display: block;
  align-items: center;
}

.ramka4 div p{
  margin-top: -20px;
  font-size: 11px;
  color: rgba(18, 18, 18, 0.8);
  font-weight: 600;
  line-height: 15px;
}
.ramka4 img{
  width: 200px;
  margin-left: -25px;
  margin-top: -15px;
}
.ramka4 p{
  margin: 0;
  color: rgba(18, 18, 18, 0.7);
  font-size: 12px;
  padding-right: 60px ;
}

.ramka5 img{
  position: absolute;
  width: 80px;
  right: 1%;
  bottom: 45%;
}
span{
  color: rgba(99, 97, 97, 0.8);
}
</style>