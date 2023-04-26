<template>
  
<header>
<AppHeader/>
</header>

<main>
<AppMain/>
</main>

<footer>
<AppFooter/>
</footer>


</template>


<script>
import AppFooter from './components/AppFooter.vue';
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue'
export default{
  name:'Appvue',
  components:{
    AppHeader,
    AppMain,
    AppFooter,
}
}

</script>

<style lang="scss" scoped>


</style>