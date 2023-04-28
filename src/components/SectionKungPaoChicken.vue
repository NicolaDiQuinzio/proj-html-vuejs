<template>
 <div class="container-fluid bg-img mt-5 ">
    
   
    <small> KUNG PAO CHICKEN - 32$</small>

 </div>


</template>


<script>
export default{
    name: 'SectionKungPaoChicken'
}

</script>

<style lang="scss" scoped>
img{
    width: 100%;
}
.bg-img{
   position: relative;
   height: 450px;
   background-image: url(../assets/img/page52x.jpg);
   background-position:center;
    background-size:cover;
    background-repeat: no-repeat;
}
small{position: absolute;
     top: 90%;
      left: 50%;
      transform: translate(-50%, -50%);
     color: white;
      font-size: 15px;
}


</style>