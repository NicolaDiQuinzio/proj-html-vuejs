<template>
    <li>
        <a href="" class="text-black icon">
            <i :class="`${icon}`"></i>
        </a>
    </li>
</template>

<script>
    export default {
        name: 'SocialComponent',
        props: ['icon']
    }
</script>

<style lang="scss" scoped>

.icon {
width: 20px;
height: 20px;
border: 2px solid white;
background-color: white;
border-radius: 50%;
padding: 8px;

}
    
</style>