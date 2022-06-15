<template>
  <main>
    <MainCardsImages/>
    <MainWorkingProcess/>
    <MainWorkWithUs/>
  </main>
</template>

<script>
import MainCardsImages from '../../Components/Sections/MainCardsImages'
import MainWorkingProcess from '../../Components/Sections/MainWorkingProcess'
import MainWorkWithUs from '../../Components/Sections/MainWorkWithUs'

export default {
    name: 'BaseMain',
    components: {
        MainCardsImages,
        MainWorkingProcess,
        MainWorkWithUs,
    }
}
</script>

<style>

</style>