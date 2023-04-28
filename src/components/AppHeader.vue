<template>
 <div class="container-fluid">
    <div class="row">
        <div class="col-md-5 bg-black p-4">
<img src="../assets/img/logo-restaurant-2x-600x115.png" alt="">
<div class="text-white m-5">
    <div class="col-md-6">
    </div>
    <div>
    <small> <span class="pr-2"> </span>THE BEST TABLE IN TOWN</small></div>
    <h1 class="font-weight-light mt-4">FINE DINING EXPERIENCE</h1>
    <p class="mt-4">Pellentesque vitae viverra risus,sagittis.Venenatis ridiculus scelerisque nisi in urna nulla.Sit tempor a et nisi ,ac felicis.
    </p>
    <ComponentButton :text="'EXPLORE THE MENU'" />
</div>
        </div>
        <div class="col-md-7 bg-img p-4">
            <ul class="mb-0 d-flex align-items-center gap-4 ">
    <li v-for="(link, index) in navbar" :key="index" class="d-flex align-items-center small">
   <a class="text-decoration-none text-white" href="">{{ link.text }} </a>
    </li>
   </ul>
     </div>
    </div>

 </div>        
  </template>
  
  <script>
  import ComponentButton from './ComponentButton.vue';
  import {headerLinks} from '../data/store';
  export default {
    name:'AppHeader',
    components:{ComponentButton},
    props:['icon'],
    data() {
        return {
           navbar: headerLinks,
        }
    }
}
    
  </script>

  
<style lang="scss" scoped>

//width img
img{
    width: 230px;
}
//background-img
.bg-img{
    background-image: url(../assets/img/slider52x.jpg);
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
}
 

</style>

