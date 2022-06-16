<template>
  <main>
    <MainHeroSlider/>
    <MainCardsImages/>
    <MainWorkingProcess/>
    <MainWorkWithUs/>
    <MainBlog/>
  </main>
</template>

<script>
import MainHeroSlider from '../../Components/Sections/MainHeroSlider'
import MainCardsImages from '../../Components/Sections/MainCardsImages'
import MainWorkingProcess from '../../Components/Sections/MainWorkingProcess'
import MainWorkWithUs from '../../Components/Sections/MainWorkWithUs'
import MainBlog from '../../Components/Sections/MainBlog'

export default {
    name: 'BaseMain',
    components: {
        MainHeroSlider,
        MainCardsImages,
        MainWorkingProcess,
        MainWorkWithUs,
        MainBlog
    }
}
</script>

<style>

</style>