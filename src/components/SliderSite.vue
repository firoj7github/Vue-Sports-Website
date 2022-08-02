<template>
  <div class="slider-all">
  <div class="slider">
    <div class="slider-1">
     <h1>Come With Us</h1>
     <p>We have programs for all levels of ability, and coaches and mentors in place to help you training, plate-loaded machines, lifting racks and cable motion.</p>
     <button>Start Now</button>
    </div>
    <div class="slider-2">
      <img src="../assets/image/1.png" alt="">
    </div>

  </div>
  </div>
</template>

<script>


export default {
  name: 'SliderSite',
  
}
</script>

<style>
.slider-all{
    background-color: rgb(15, 13, 13);
    width: 100%;
    height: 550px;
}
.slider{
  display: grid;
  grid-template-columns: repeat(2, 1fr);
}
.slider-1{
  margin-top: 130px;
  color:white;
  width: 450px;
  margin-left: 120px;
}
.slider-1 button{
 padding-left: 15px;
 padding-right: 15px;
 padding-top: 5px;
 padding-bottom: 5px;
 background-color: chocolate;
 font-size: 17px;
 color: white;
 border-radius: 3px;
}
.slider-1 h1{
  font-size: 55px;
  font-weight: 700;
}
</style>