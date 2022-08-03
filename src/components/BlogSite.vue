<template>
  <div class="blog-all">
         <div class="blog">
        <div class="blog-1">
            <h1>Fitness First ...</h1>
            <p>Our fitness suites feature the hottest new equipment out at the moment, including a SYNRGY360 training area, WLinear training rig, Watt bikes and the latest cardio equipment from Life Fitness all connected by the LFconnect app to track your work outs. <br><br> Our spacious and light fitness suites have dedicated areas for cardio, fixed weights, free weights, functional training, plate-loaded machines, lifting racks and cable motion.</p>
        </div>
        <div class="blog-2">
            <img src="../assets/image/500.png" alt="">
        </div>
    </div>
    
   
  </div>
</template>

<script>


export default {
  name: 'BlogSite',
  
}
</script>

<style>
.blog-all{
    width: 100%;
    height: 700px;
     background-color: rgb(27, 26, 26);
     clip-path: polygon(0 28%, 100% 1%, 100% 100%, 0% 100%);
     margin-top: -196px;
     z-index: 1;
}
.blog{
    display: grid;
    grid-template-columns: repeat(2, 1fr);
}
.blog-2 img{
    height: 600px;
    margin-top: 130px;
}
.blog-1 h1{
  margin-top: 320px;
  
  font-size: 45px;
  font-weight: 700;
}
.blog-1{
color: white;
margin-left: 70px;
width: 465px;
}
    


</style>