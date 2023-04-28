<template>

<SectionCaliforniaRolls/>
<SectionImgpng/>
<SectionBestTable/>
<SectionNewYork/>
<SectionKungPaoChickenVue/>
<SectionCards/>
<SectionTakeOut/>
<SectionMenu/>
<SectionBriased/>


</template>


<script>
import SectionCaliforniaRolls from './SectionCaliforniaRolls.vue';
import SectionImgpng from './SectionImgpng.vue';
import SectionBestTable from './SectionBestTable.vue';
import SectionNewYork from './SectionNewYork.vue';
import SectionKungPaoChickenVue from './SectionKungPaoChicken.vue';
import SectionCards from './SectionCards.vue'
import SectionTakeOut from '../components/SectionTakeOut.vue'
import SectionMenu from './SectionMenu.vue';
import SectionBriased from '../components/SectionBraised.vue'

export default {
    name:'AppMain',
    components:{SectionCaliforniaRolls,
         SectionImgpng,
         SectionBestTable,
          SectionNewYork,
          SectionKungPaoChickenVue,
          SectionCards,
          SectionTakeOut,
          SectionMenu,
          SectionBriased,
        }
}

</script>

<style lang="scss" scoped>


</style>