<template>
<div class="container-fluid bg-black text-white">
    <div class="row">
        <div class="col-md-7 img-bg">
        </div>
        <div class="col-md-4 p-5 mx-5 text-left">
        <p class="mt-4 ">FINE DINING EXPERIENCE </p>
        <h2 class="mt-4">THE BEST TABLE IN TOWN </h2>
      <p class="mt-4">  Pellentesque vitae viverra risus, sagittis. Venenatis ridiculus scelerisque nisi in urna nulla. 
      </p>
      <ComponentButton :text="'EXPLORE THE MENU'" />
        </div>
    </div>
</div>

</template>


<script>

import ComponentButton from './ComponentButton.vue';
export default{
    name: 'SectionBestTable',
    components:{ComponentButton},
    
}

</script>

<style lang="scss" scoped>
.img-bg{
    background-image: url(../assets/img/slider32x.jpg);
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
}

</style>