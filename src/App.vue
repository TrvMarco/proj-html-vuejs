<template>
  <div id="app">
    <BaseHeader/>
  </div>
</template>

<script>
import BaseHeader from './Components/Blocks/BaseHeader'

export default {
  name: 'App',
  components: {
    BaseHeader,
  }
}
</script>

<style lang="scss">
  @import 'assets/style/global-style.scss'
</style>
