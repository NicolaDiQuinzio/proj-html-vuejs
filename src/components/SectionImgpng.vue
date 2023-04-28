<template>
    <div class="ms-container mx-auto h-100 mb-5 ">
        <div class="d-flex flex-column h-100 justify-content-evenly">
            <div class="container p-5">
                <div class="row gap-5">
                    <div class="col text-center" v-for="sushi in sushi">
                         <img :src="getImagePath(`../assets/img/${sushi.src}`)" alt=""> 
                       <hr class="w-50">
                        <h5 class="mb-4 mt-4">{{ sushi.title }}</h5>
                        <p>{{ sushi.text }}</p>
                        <button class="btn-h mt-2">{{ sushi.btn }}</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>


<script>
import {sushi} from '../data/store'
export default{
    name: 'SectionImgpng',
    data() {
        return {
            sushi: [...sushi]
        };
    },
    methods: {
     getImagePath: function (imgPath) {
            return new URL(imgPath, import.meta.url).href;
        }
    },
   
}

</script>

<style lang="scss" scoped>
.btn-h {
background-color: transparent;
color: black;
border: 0.2px solid black;
padding: 10px 25px;
font-size: 16px;
transition: all 0.3s ease;
}

.btn-h:hover {
background-color: black;
color: white;
border-color: white;
}

</style>