<template>
    <section>
<div class="container-sm  mt-5">
   <h1 class="text-center mb-5"> Latest news & promotions</h1>
   <div class="row d-flex justify-content-center pt-5 gap-3">
    <div class="text-center" style="width: 18rem;">
  <img class="card-img-top" src="../assets/img/blog92x-200x229.jpg" alt="Card image cap">
  <div class="card-body">
    <h5 class="card-title mt-3"> THE BEST COFFE IN TOWN</h5>
    <p class="card-text"> </p>
  </div>
 </div>
 <div class="text-center card-w ">
  <img class="card-img-top" src="../assets/img/blog72x.jpg" alt="Card image cap">
  <div class="card-body">
    <h5 class="card-title">Card title</h5>
    <p class="card-text"></p>
  </div>
 </div>
 <div class="text-center" style="width: 18rem;">
  <img class="card-img-top" src="../assets/img/blog82x-200x229.jpg" alt="Card image cap">
  <div class="card-body">
    <h5 class="card-title">Card title</h5>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
  </div>
 </div>

 

   </div>
</div>
</section>

</template>


<script>
export default{
    name: 'SectionCards'
}

</script>

<style lang="scss" scoped>
.card-w{
    width: 18rem;
    

}
 .card-img-top{ 
    transition: all 1s ease-out; 
} 
.card-img-top:hover{
   
     transform: scaleY(1.1);
} 
.card-img-top:hover + .card-body{ 
    margin-top: 100%; opacity: 0; visibility: hidden; 
}

</style>