<template>
  <section class="hero-slider">
    <div class="container-fluid">
    <div class="row align-items-center">
        <div class="col-lg-6 d-flex justify-content-between align-items-center">
            <button class="btn-circle d-none d-lg-block">
                    <i class="fa-solid fa-chevron-left"></i>
            </button>
            <div class="hero-text">
                <h1 class="display-2 pb-3">Devotion that never <span class="italic-font">ends</span></h1>
                <p class="pb-3">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sed voluptates quia nemo iusto asperiores aliquid omnis.</p>
                <button class="btn-custom btn-border-pink">Read More</button>
            </div>
        </div>
        <div class="col-lg-6 d-flex justify-content-between align-items-center">
            <img class="img-fluid" src="../../assets/img/hero-slider.png" alt="Art image slider">
            <button class="btn-circle d-none d-lg-block">
                <i class="fa-solid fa-chevron-right"></i>
            </button>
        </div>
        <div class="col-12 d-flex justify-content-center pt-2">
            <button class="btn-circle slider"></button>
            <button class="btn-circle slider"></button>
            <button class="btn-circle slider active"></button>
        </div>
    </div>
  </div>
  </section>
</template>

<script>
export default {
    name: 'MainHeroSlider'
}
</script>

<style lang="scss" scoped>
    .hero-slider{
        padding: var(--padding-hero-slider);

        img{
            max-width: 90%;
        }
    }

    .hero-text{
        width: 70%;
    }
</style>