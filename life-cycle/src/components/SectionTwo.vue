<template>
  <section class="main">

    <div class="second-pic">
      <div class="ramka3">
        <p class="text">Подкатегория 2</p>
        <div>
          <img src="../assets/section-2/Subtract(4).png" alt="photo">
          <p>Шерзод Асадов анонсировал события новой рабочей недели Президента </p>
        </div>
      </div>

      <div class="ramka4">
        <p class="text">Подкатегория 2</p>
        <div>
          <img src="../assets/section-2/Subtract(1).png" alt="photo">
          <p>Шерзод Асадов анонсировал события новой рабочей недели Президента <br><span>08.05.2021</span></p>
        </div>
      </div>

      <div class="ramka5">
        <p class="text">Подкатегория 2</p>
        <div>
          <img src="../assets/section-2/Subtract.png" alt="photo">
          <p>Шерзод Асадов анонсировал события новой рабочей недели Президента <br><span>08.05.2021</span></p>
        </div>
      </div>

    </div>
    <div class="first-pic">
      <div class="ramka1">
        <p class="text">Подкатегория 2</p>
        <div>
          <img src="../assets/section-2/Subtract(2).png" alt="photo">
          <p>Шерзод Асадов анонсировал события новой рабочей недели Президента <br><span>08.05.2021</span></p>
        </div>
      </div>

      <div class="ramka2">
        <p class="text">Подкатегория 2</p>
        <div>
          <img src="../assets/section-2/Subtract(3).png" alt="photo">
          <p>Шерзод Асадов анонсировал события новой рабочей недели Президента <br><span>08.05.2021</span></p>
        </div>
      </div>

    </div>


  </section>
</template>

<script>
export default {

}
</script>

<style>
section{
  background-image: url('../assets/section-2/bg.png');
  /* background-attachment: fixed; */
  background-position: center;
  background-repeat: no-repeat;
  /* background-size: cover; */
}

.first-pic{
  display: flex;
  justify-content: center;
}

.first-pic .ramka1 img{
  width: 250px;
}

.ramka1{
  /* width: 500px; */
  display: block;
  margin-top: -10px;
}

.ramka1 .text{

  font-size: 8.5px;
  color: rgba(79, 79, 79, 0.7);
  color: #4F4F4F;
  font-weight: 600;
  line-height: 15px;
  position: absolute;
  margin-top: 2.5px;
  margin-left: 160px;
}
span{
  color: rgba(79, 79, 79, 0.8)
}

.ramka1 div p{
  width: 280px;
  font-size: 11px;
  color: rgba(18, 18, 18, 0.8);
  font-weight: 600;
  padding-right:  250px;
}

.first-pic .ramka2 img{
  width: 300px;
}

.ramka2 .text{

  font-size: 8.5px;
  color: rgba(79, 79, 79, 0.7);
  color: #4F4F4F;
  font-weight: 600;
  line-height: 15px;
  position: absolute;
  margin-top: 2.5px;
  margin-left: 110px;
}

.ramka2{
  /* width: 500px; */
  display: block;
  margin-top: 20px;
}

.ramka2 div{
  display: flex;
  justify-content: center;
  align-items: center;
}
.ramka2 div p{
  width: 280px;
  font-size: 11px;
  color: rgba(18, 18, 18, 0.8);
  font-weight: 600;
  padding-left: 10px;
}
.second-pic{
  display: flex;
  justify-content: center;
}

.ramka3{
  margin-left: 30px;
  margin-top: 50px;
}
.ramka3 p{
  /* margin-top: -20px; */
  font-size: 12.5px;
  color: #4F4F4F;
  font-weight: 600;
  line-height: 20px;
  width: 300px;
}

.ramka3 .text{
  font-size: 9.5px;
  color: rgba(79, 79, 79, 0.7);
  font-weight: 600;
  line-height: 15px;
  position: absolute;
  left: 8.6%;
  margin-top: -6.5px;
  margin-left: 20px;
}
.ramka3 img{
  width: 290px;
}

.ramka4{
  margin-left: 70px;
  padding-top: 100px;
}
.ramka4 img{
  width: 250px
}

.ramka4 p{
  /* margin-top: -20px; */
  font-size: 12.5px;
  color: #4F4F4F;
  font-weight: 600;
  line-height: 20px;
  width: 300px;
}

.ramka4 p span{
  color: rgba(79, 79, 79, 0.8);
}

.ramka4 .text{
  font-size: 9.5px;
  color: rgba(79, 79, 79, 0.7);
  color: #4F4F4F;
  font-weight: 600;
  line-height: 15px;
  position: absolute;
  margin-top: 5.5px;
  margin-left: 20px;
}


.ramka5{
  margin-left: 180px;
  margin-top: 20px;
}
.ramka5 img{
  width: 350px
}

.ramka5 p{
  /* margin-top: -20px; */
  font-size: 12.5px;
  color: #4F4F4F;
  font-weight: 600;
  line-height: 20px;
  width: 300px;
  padding-left: 40px;
}

.ramka5 p span{
  color: rgba(79, 79, 79, 0.8);
}

.ramka5 .text{
  font-size: 9.5px;
  color: rgba(79, 79, 79, 0.7);
  color: #4F4F4F;
  font-weight: 600;
  line-height: 15px;
  position: absolute;
  margin-top: 10.5px;
  margin-left: -40px;
  text-align: center;
}

</style>