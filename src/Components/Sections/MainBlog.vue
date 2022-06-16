<template>
  <section class="blog container">
    <div class="row justify-content-center gy-5">
        <div class="col-lg-4 container">
            <div class="blog-calendar">
                <p class="italic-font date">07</p>
                <p><small>MAY '19</small></p>
            </div>
            <img class="img-fluid pb-4" src="../../assets/img/h-2-blog-img-1.jpg" alt="Article image">
            <h4 class="pb-3">This Way, loves: a detailed guide through new design</h4>
            <small class="italic-font">By Emily Fields</small>
        </div>
        <div class="col-lg-4 container">
            <div class="blog-calendar">
                <p class="italic-font date">07</p>
                <p><small>MAY '19</small></p>
            </div>
            <img class="img-fluid pb-4" src="../../assets/img/h-2-blog-img-2.jpg" alt="Article image">
            <h4 class="pb-3">I try to give people a different way of looking art</h4>
            <small class="italic-font">By Emily Fields</small>
        </div>
        <div class="col-lg-4 container">
            <div class="blog-calendar">
                <p class="italic-font date">07</p>
                <p><small>MAY '19</small></p>
            </div>
            <img class="img-fluid pb-4" src="../../assets/img/h-2-blog-img-3.jpg" alt="Article image">
            <h4 class="pb-3">Introduce Richard Laperrière of those amazing features</h4>
            <small class="italic-font">By Emily Fields</small>
        </div>
    </div>
  </section>
</template>

<script>
export default {
    name: 'MainBlog',
}
</script>

<style lang="scss" scoped>
    .blog{
        padding: var(--padding-section);
    }

    .blog-calendar{
        width: 4.375rem;
        height: 4.375rem;
        position: absolute;
        top: -1.25rem;
        left: 1.875rem;
        background-image: url('../../assets/img/blog-calendar.png');
        background-size: contain;
        font-weight: bold;
        text-align: center;
        box-shadow: 2px 2px 4px 1px rgba(87, 87, 87, 0.39)
    }

    .date{
        font-size: 1.25rem;
        margin-bottom: .625rem;
    }
    
    .container{
        position: relative;
    }
</style>