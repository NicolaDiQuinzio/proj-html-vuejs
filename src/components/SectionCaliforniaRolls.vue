<template>
<div class="container-sm">
    <div class="row">
    <div class="col-md-6 p-5">
<p class="pt-5"><strong> HAC TELLUS, FELIS RISUS AT</strong> mattis mattis.Eget euismod semper eget tortor, donec amet,blandit.Tristique facilisi faucibus elementum feugiat in nam in feugiat.Ipsum odio etiam duis facilisis amet vulputate.
</p>
<h1 class="font-weight-light ">FOOD IS OUR COMMON GROUND, A UNIVERSAL EXPERIENCE.</h1>
<p class="pt-4">Tristique tempus condimentum diam donee. Condimentum ullamcorper sit elemntum hendrerit mi nulla in conseuat,ut.Metus,nullam scelerisque netus viverra dui.
</p>
<img src="../assets/img/signature.jpg" class="signature pt-3" alt="">
    </div>
    <div class="col-md-5 p-5 relative">
 <img src="../assets/img/info22x.jpg" class="img-width" alt="">
 <small class="text-white pic-info"> CALIFORNIA ROLLS- 22$</small>
    </div>
 </div>
</div>

</template>


<script>
export default{
    name: 'SectionCaliforniaRolls'
}

</script>

<style lang="scss" scoped>
.img-width{
    width: 450px;
    position: relative;
}

.img-width:hover {
  box-shadow: 3px 3px 5px rgba(0,0,0,0.5);
}
.relative{
position: relative;}
.pic-info{
    position: absolute;
      top: 90%;
      left: 60%;
      transform: translate(-50%, -50%);
      font-size: 10px;
      font-weight: bold;
}

.signature{
    width: 130px;
}



</style>