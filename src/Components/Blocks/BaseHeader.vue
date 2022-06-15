<template>
    <header>
        <div class="container-fluid d-flex justify-content-between align-items-center">
            <div class="_logo">
                <img src="../../assets/img/logo-sidearea-1.png" alt="Marée logo">
            </div>
            <div class="_nav-bar">
                <NavBar/>
            </div>
        </div>
    </header>
</template>

<script>
import NavBar from '../Common elements/NavBar' 

export default {
    name: 'BaseHeader',
    components: {
        NavBar,
    }
}
</script>

<style lang="scss" scoped>
    header{
        display: flex;
        align-items: center;
        height: 5rem;
    }
</style>