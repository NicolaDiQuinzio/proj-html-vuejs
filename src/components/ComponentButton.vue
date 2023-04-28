<template>
 <button type="button" class="mt-4 mb-5 btn-h">{{ text }}</button>


</template>


<script>
export default{
    name: 'ComponentButton',
    props:['text']
}

</script>

<style lang="scss" scoped>
.btn-h {

background-color: transparent;
color: white;
border: 1px solid white;
padding: 10px 25px;
font-size: 16px;
transition: all 0.3s ease;
}

.btn-h:hover {
background-color: white;
color: black;
border-color: black;
}
</style>