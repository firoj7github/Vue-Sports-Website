<template>
 <div class="clip-all">
    <div class="clip">
        <div class="clip-1">
            <h1>Discover new Activity</h1>
            <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt.
            <br><br> Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab.</p>
        </div>
        <div class="clip-2">
            <img src="../assets/image/fdgg-min.jpg" alt="">
            <img src="../assets/image/fdgg-min.jpg" alt="">
        </div>
    </div>
 </div>

</template>

<script>


export default {
  name: 'ClipSite',
  
}
</script>

<style>
.clip-all{
    width: 100%;
    height: 800px;
     background-color: rgb(15, 13, 13);
}
.clip{
    display: grid;
    grid-template-columns: repeat(2, 1fr);

}
.clip-1{
    width: 1000px;
    height: 1070px;
    background-color: rgb(27, 26, 26);
 clip-path: polygon(71% 0, 71% 23%, 93% 23%, 100% 100%, 0 100%, 0 24%);
    margin-top: -290px;
}
.clip-1 h1{
    color: white;
    margin-left: 140px;
    margin-top: 430px;
    font-size: 50px;
    font-weight: 700;
}
.clip-1 p{
    width: 450px;
     margin-left: 140px;
     color: white;
}
.clip-2{
    display: grid;
    grid-template-columns: repeat(2, 1fr);
}
.clip-2 img{
    width: 250px;
    height: 350px;
   margin-left: -100px;
   z-index: 1;
}
  

</style>
