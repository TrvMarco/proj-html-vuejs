<template>
  <ul>
    <li>LINK</li>
    <li>LINK</li>
    <li>LINK</li>
    <li>LINK</li>
    <li>LINK</li>
    <li>LINK</li>
    <li>LINK</li>
    <li><img src="../../assets/img/svg-1.svg" alt="menù svg"></li>
    </ul>
</template>

<script>
export default {
    name: 'NavBar'
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/mixins.scss';

ul{
    @include navBarStyle
}
</style>