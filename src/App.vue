<template>
  <div id="app">
    <BaseHeader/>
    <BaseMain/>
  </div>
</template>

<script>
import BaseHeader from './Components/Blocks/BaseHeader'
import BaseMain from './Components/Blocks/BaseMain'

export default {
  name: 'App',
  components: {
    BaseHeader,
    BaseMain,
  }
}
</script>

<style lang="scss">
  @import 'assets/style/global-style.scss'
</style>
