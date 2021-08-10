<template>
  <section class="section-3">
    <div class="picture">
      <img src="../assets/section-3/picture.png" alt="img">
    </div>

    <div class="list">
       <div class="picture-1">
        <p class="text">Подкатегория 2</p>
        <div>
          <img src="../assets/section-3/home.png" alt="photo">
          <p>Шерзод Асадов анонсировал события новой рабочей недели Президента <br><span>08.05.2021</span></p>
        </div>
      </div>
       <div class="picture-2">
        <p class="text">Подкатегория 2</p>
        <div>
          <img src="../assets/section-3/home.png" alt="photo">
          <p>Шерзод Асадов анонсировал события новой рабочей недели Президента <br><span>08.05.2021</span></p>
        </div>
      </div>
    </div>
    <div class="picture2">
      <img src="../assets/section-3/picture2.png" alt="img">
      <p>Шерзод Асадов анонсировал события новой рабочей недели Президента <br><span>08.05.2021</span></p>
      
    </div>

    <div class="left-pic">
      <img src="../assets/section-3/left-photo.png" alt="img">
      <p>Шерзод Асадов анонсировал события новой рабочей недели Президента <br><span>08.05.2021</span></p>
    </div>

    <div class="right-pic">
      <img src="../assets/section-3/right-photo.png" alt="img">
      <p>Шерзод Асадов анонсировал события новой рабочей недели Президента <br><span>08.05.2021</span></p>
    </div>
  </section>
</template>

<script>
export default {
  
}
</script>

<style>
.section-3{
  position: relative;
  background-image: url('../assets/section-3/background.png');
  background-size: 98%  1000px;
  background-repeat: no-repeat;
  min-height: 1250px;
}
.picture img{
  width: 1242px;
  height: 890px;
  margin-top: -21.9px;
  margin-left: 12px;
}

.list{
  position: absolute;
  left: 25%;
  top: 19%;
}
.picture-1 .text{
  color: rgba(255, 255, 255, 0.7);
  margin-left: -2px;
  padding: 0;
}

.picture-1 div{
  display: flex;
  align-items: center;
}

.picture-1 img{
  width: 100px;
  height: 90px;
}

.picture-1 p{
  width: 150px;
  color: #FFFFFF;
  line-height: 16px;
  font-size: 12px;
  margin-left: 10px;
}
.picture-2 img{
  width: 100px;
  height: 90px;
}

.picture-2 .text{
  color: rgba(255, 255, 255, 0.7);
  margin-left: -2px;
  margin-top: 20px;
  padding: 0;
}
.picture-2 div{
  display: flex;
  align-items: center;
}

.picture-2 p{
  width: 150px;
  color: #FFFFFF;
  line-height: 16px;
  font-size: 12px;
  margin-left: 10px;
}
span{
  color: rgba(255, 255, 255, 0.8);
}

.picture2{
  position: absolute;
  top: 13%;
  right: 22%;
}
.picture2 img{
  transform: rotate(3.8deg);;
  width: 320px;
  border-radius: 4px;
}

.picture2 p{
  width: 300px;
  color: rgba(79, 79, 79, 0.8);
  line-height: 20px;
  font-size: 12px;
  font-weight: bold;
  position: absolute;
  right: -15%;
  top: 70%;
  transform: rotate(-25.06deg);;
}
.picture2 p span{
  color: rgba(79, 79, 79, 0.8);
  font-weight: 300;
}

.left-pic{
  position: absolute;
  bottom: 30%;
}
.left-pic img{
  width: 220px;
  margin-left: 90px;
  margin-bottom: 10px;
}

.left-pic p{
  width: 300px;
  color: rgba(79, 79, 79, 0.8);
  line-height: 15px;
  font-size: 12px;
  font-weight: bold;
  padding-left: 80px;
  padding-bottom: 20px;
}
.left-pic p span{
  color: rgba(79, 79, 79, 0.8);
  font-weight: 300;
}

.right-pic{
  position: absolute;
  bottom: 33%;
  right: -1%;
}
.right-pic img{
  width: 195px;
  margin-left: 96px;
  margin-bottom: 10px;
}

.right-pic p{
  width: 300px;
  color: rgba(79, 79, 79, 0.8);
  line-height: 15px;
  font-size: 12px;
  font-weight: bold;
  padding-left: 80px;
  padding-bottom: 20px;
}
.right-pic p span{
  color: rgba(79, 79, 79, 0.8);
  font-weight: 300;
}
</style>