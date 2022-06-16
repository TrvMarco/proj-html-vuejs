<template>
    <section class="working-process container">
        <h2 class="text-center display-4">Working <span class="italic-font">process</span></h2>
        <div class="row justify-content-center text-center p-4">
            <div class="col-lg-3">
                <div>
                    <div class="circle mb-4"><i class="fa-solid fa-lightbulb"></i></div>
                    <h5 class="pb-2">First theres an idea</h5>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam labore debitis amet</p>
                </div>
            </div>
            <div class="col-lg-3">
                <div>
                    <div class="circle mb-4"><i class="fa-regular fa-comment"></i></div>
                    <h5 class="pb-2">Than we talk about</h5>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam labore debitis amet</p>
                </div>
            </div>
            <div class="col-lg-3">
                <div>
                    <div class="circle mb-4"><i class="fa-solid fa-cloud"></i></div>
                    <h5 class="pb-2">And we think about</h5>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam labore debitis amet</p>
                </div>
            </div>
            <div class="col-lg-3">
                <div>
                    <div class="circle mb-4"><i class="fa-solid fa-pen-fancy"></i></div>
                    <h5 class="pb-2">So we draw along</h5>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam labore debitis amet</p>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'MainWorkingProcess'
}
</script>

<style lang="scss" scoped>
    .working-process{
        padding: var(--padding-section);
    }

    .row{
        background-image: url('../../assets/img/svg-3.svg');
        background-repeat: no-repeat;
        background-position-x: center;
        background-position-y: 15%;
        background-size: 70%;
    }

    .circle{
        margin: auto;
        height: 7.5rem;
        width: 7.5rem;
        border-radius: 50%;
        background-color: var(--circle-color);
        font-size: 2.5rem;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .fa-lightbulb{
        color: var(--lamp-color) ;
    }

    .fa-comment{
        color: var(--mex-color);
    }

    .fa-cloud{
        color: var(--cloud-color);
    }

    .fa-pen-fancy{
        color: var(--pen-color);
    }

</style>