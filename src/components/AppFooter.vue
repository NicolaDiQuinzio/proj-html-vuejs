<template>

<div class="container-fluid bg-img ">
    <div class="d-flex justify-content-center align-content-center flex-column pt-5 text-center">
        <div class="d-flex justify-content-center align-content-center m-5">
<img src="../assets/img/logo-restaurant-2x-600x115.png" alt="">
</div>
<h5 class="text-white m-5"> Quam eu proin sit massa condimentum. Volutpat non pulvinar <br>
aliquet nunc. Quam eu proin sit massa condimentum. </h5>
<div class="d-flex justify-content-center align-items-center fs-3 mb-5 ">
    <span v-for="social in socials" :key="social.icon"> <ComponentSocialVue :icon="social.icon" /> </span>

</div>
</div>
</div>


</template>


<script>
import { socials } from '../data/store';
import ComponentSocialVue from '../components/ComponentSocial.vue'
export default{
    name: "AppFooter",
    components: { ComponentSocialVue },
    data() {
        return {
            socials: [...socials]
        }
    }
}


</script>

<style lang="scss" scoped>
.bg-img{
    background-image: url(../assets/img/footer2x.jpg);
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
}

img{
    width: 300px;
}
span{
   
}

</style>