<template>
 <div class="container-fluid bg-img mt-5 ">
     <div class="row d-flex justify-content-start align-items-start p-5">
    <div class="col-md-5 bg-black text-white text-left bg-img2 m-3 p-4 bg-hover">
        <h1 class=" m-4 fs-1"> BRAISED ABALONE </h1>
        <hr class="w-25">
        <p class="p-4"> 
        Non arcu mauris tortor ultrices mollis tellus euismod fermentum. Habitant amet tincidunt id sapien accumsan sed at. <br>
    <span>Mmalesuada ullamcorper amet. Pretium pretium dignissim nisi.</span> 
      </p>
      <ComponentButton  :text="'READ FULL ARTICLE'" class="m-4" />
    </div>
 </div>

 </div>

</template>


<script>
import ComponentButton from './ComponentButton.vue';
export default{
    name: 'SectionBraised',
    components:{ComponentButton}
}

</script>


<style>
.bg-img{
   height: 600px;
   background-image: url(../assets/img/hero42x.jpg);
   background-position:center;
    background-size:cover;
    background-repeat: no-repeat;
}

</style>