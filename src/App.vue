<template>
  <div id="app">
    <BaseHeader/>
    <BaseMain/>
    <BaseFooter/>
  </div>
</template>

<script>
import BaseHeader from './Components/Blocks/BaseHeader';
import BaseMain from './Components/Blocks/BaseMain';
import BaseFooter from './Components/Blocks/BaseFooter';

export default {
  name: 'App',
  components: {
    BaseHeader,
    BaseMain,
    BaseFooter
  }
}
</script>

<style lang="scss">
  @import 'assets/style/global-style.scss'
</style>
