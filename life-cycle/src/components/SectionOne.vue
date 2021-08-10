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
      <p class="text">Подкатегория 2</p>
      </div>
      <div class="subtract">
        <img src="../assets/Subtract.png" alt="photo">
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
  background-attachment: fixed;
  /* background-position: center; */
  background-repeat: no-repeat;
  /* background-size: cover; */
  background-size:  1290px 670px ;
  min-height: 670px;
  margin: 0 auto;
}
.zametka{
  position: absolute;
  top: 31%;
  left: 19%;
  width: 80px;
}
.ramka {
  position: absolute;
  display: block;
  width: 260px;
  left: 33%;
  top: 15%
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
  top: 49%
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
  width: 200px;
}
.ramka1 img{
  width: 200px;
  margin-left: -25px;
  margin-top: -58px;
}
.ramka1 p{
  color: rgba(18, 18, 18, 0.7);
  font-size: 12px;
  padding-right: 50px;
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
  margin-top: -13px;
  padding: 0;
  font-size: 10.5px;
  color: rgba(18, 18, 18, 0.8);
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
.ramka3{
  position: absolute;
  left: 30%;
  bottom: 6%;
}

.ramka3 img {
  position: absolute;
  width: 430px;
  bottom: 0;
}

.ramka3 .laptop-bg{
  margin-bottom: 95px;
  margin-left: 55.5px;
  width: 322px;
}

.ramka3 .text{
  position: absolute;
  bottom: 75%;
  left: 20%;
  color: rgba(18, 18, 18, 0.7);
  font-size: 9px;
  width: 100px;
}
.subtract {
  display: flex;
  justify-content: space-around;
  align-items: center;
  margin-bottom: 350px;
  margin-left: 300px;
}
.subtract img{
  width: 169px;
  position: absolute;
  bottom: 44.95%;
  left: 20.1%;
}

.subtract .laptop-text{
  position: absolute;
  bottom: 50%;
  left: 50.2%;
  width: 130px;
  margin-left: 83px;
  font-size: 9px; 
  color: white;
  font-weight: 700;
  line-height: 14px;
}
.ramka3 .laptop-header{
  width: 318.55px;
  margin-left: 56.6px;
  margin-bottom: 293px;
}

.laptop-text span{
  color: rgba(255, 255, 255, 0.8);
  font-weight: 400;
}

.ramka3 .laptop-footer{
  position: fixed;
  width: 280.95px;
  margin-bottom: 105px;
  margin-left: 73px;
}

.ramka4 {
  position: absolute;
  display: block;
  width: 260px;
  right: 15%;
  bottom: 20%
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
  width: 200px;
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
  bottom: 32%;
}
span{
  color: rgba(99, 97, 97, 0.8);
}
</style>