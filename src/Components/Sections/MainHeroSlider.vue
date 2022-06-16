<template>
  <section class="hero-slider">
    <div class="container-fluid">
    <div class="row align-items-center">
        <div class="col-lg-6 d-flex justify-content-end">
            <div class="hero-text">
                <h1 class="display-2">Devotion that never <span class="italic-font">ends</span></h1>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sed voluptates quia nemo iusto asperiores aliquid omnis.</p>
                <button>Read More</button>
            </div>
        </div>
        <div class="col-lg-6">
            <img src="../../assets/img/hero-slider.png" alt="Art image slider">
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
    }

    .hero-text{
        width: 70%;
    }
</style>