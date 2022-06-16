<template>
  <ul>
    <li class="d-none d-lg-block">HOME</li>
    <li class="d-none d-lg-block">PAGES</li>
    <li class="d-none d-lg-block">PORTFOLIO</li>
    <li class="d-none d-lg-block">BLOG</li>
    <li class="d-none d-lg-block">SHOP</li>
    <li class="d-none d-lg-block">ELEMENTS</li>
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
    font-weight: 500;
}

li{
    padding: 0 .1875rem;

    &:hover{
        cursor: pointer;
        background: linear-gradient(#fff 0%, #fff 45%,var(--primary-pink) 45%, var(--primary-pink) 60%);
    }
}
</style>