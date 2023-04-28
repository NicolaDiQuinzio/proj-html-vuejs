<template>
<div class="container-sm  mt-5">
   <h1 class="text-center">What critics are saying about us </h1>

   
   <div class="row d-flex justify-content-center mt-5">
    <div class="col-md-5 p bg-img">
    </div>
    <div class="col-md-5 p-5 bg-black text-white text-left bg-hover">
        <small class="mt-4 ">MAGGY STEWART </small>
        <h2 class="mt-4">NEW YORK TIMES</h2>
        <div> 
            <i v-for="n in 5" class="fa-solid fa-star"></i>
        </div>
        <hr class="w-25">
      <p class="mt-4"> 
Non arcu mauris tortor ultrices mollis tellus euismod fermentum. Habitant amet tincidunt id sapien accumsan sed at. <br>
<span>Mmalesuada ullamcorper amet. Pretium pretium dignissim nisi.</span> 
      </p>
      <ComponentButton :text="'READ FULL ARTICLE'" />
    </div>
 </div>

  
    <div class="row d-flex justify-content-center mt-3">
    <div class="col-md-5 bg-img1 m-3 bg-hover">
       </div>
    <div class="col-md-5 bg-black text-white text-left bg-img2 m-3 p-4 bg-hover">
        <small class="mt-4 ">MAGGY STEWART </small>
        <h2 class="mt-4">NEW YORK TIMES</h2>
        <div> 
            <i v-for="n in 5" class="fa-solid fa-star"></i>
       </div>
       <hr class="w-25">
        <p class="mt-4"> 
        Non arcu mauris tortor ultrices mollis tellus euismod fermentum. Habitant amet tincidunt id sapien accumsan sed at. <br>
    <span>Mmalesuada ullamcorper amet. Pretium pretium dignissim nisi.</span> 
      </p>
      <ComponentButton  :text="'READ FULL ARTICLE'" />
    </div>
 </div>
</div>


</template>


<script>
import ComponentButton from './ComponentButton.vue';
export default{
    name: 'SectionNewYork',
    components:{ComponentButton}
}

</script>

<style lang="scss" scoped>
.bg-img{
    height: 500px;
    background-image: url(../assets/img/blog72x.jpg);
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
 
}
.bg-hover{
    transition: all 0.3s ease-in-out;
}

.bg-hover:hover{
    transform: scale(1.03);
}

.bg-img1{
    height: 500px;
    width: 460px;
    background-image: url(../assets/img/info52x.jpg);
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
}


.bg-img2{
    height: 500px;
    width: 460px;
    background-image: url(../assets/img/info12x.jpg);
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
}

</style>