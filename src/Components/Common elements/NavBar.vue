<template>
  <ul>
    <li>HOME</li>
    <li>PAGES</li>
    <li>PORTFOLIO</li>
    <li>BLOG</li>
    <li>SHOP</li>
    <li>ELEMENTS</li>
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
    @include navBarStyle;
    font-weight: 700;
}

li{
    padding: 0 .1875rem;

    &:hover{
        cursor: pointer;
        background: linear-gradient(#fff 0%, #fff 45%,var(--primary-pink) 45%, var(--primary-pink) 60%);
    }
}
</style>