<template>
  <main>
    <MainCardsImages/>
    <MainWorkingProcess/>
  </main>
</template>

<script>
import MainCardsImages from '../../Components/Sections/MainCardsImages'
import MainWorkingProcess from '../../Components/Sections/MainWorkingProcess'

export default {
    name: 'BaseMain',
    components: {
        MainCardsImages,
        MainWorkingProcess,
    }
}
</script>

<style>

</style>