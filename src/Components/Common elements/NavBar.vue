<template>
  <ul>
    <li v-for="link in links" :key="link" class="d-none d-lg-block text-uppercase"><a href="#">{{link}}</a></li>
    <li class="h-menu"><img src="../../assets/img/svg-1.svg" alt="menù svg"></li>
    </ul>
</template>

<script>
export default {
    name: 'NavBar',
    data(){
        return{
            links:[
                'home',
                'pages',
                'portfolio',
                'blog',
                'shop',
                'elements'    
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/mixins.scss';

ul{
    @include navBarStyle;
    font-weight: 500;

    li{
        padding: 0 .1875rem;

        &:hover{
            cursor: pointer;
            background: linear-gradient(#fff 0%, #fff 45%,var(--primary-pink) 45%, var(--primary-pink) 60%);
        }
    }

    a{
        text-decoration: none;
        color: inherit;
    }

    .h-menu:hover{
        background: none;
    }
}

</style>