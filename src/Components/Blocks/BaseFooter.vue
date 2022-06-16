<template>
  <footer>
    <div class="container">
        <div class="row">
            <div class="col-lg-3">
            <img class="pb-2" src="../../assets/img/logo-sidearea-1.png" alt="Marée logo">
            <p>Let's Get Creative</p>
            </div>
            <div class="col-lg-3">
                <p>maree.qodo@gmail.com</p>
                <p>+44645321789</p>
            </div>
            <div class="col-lg-3">
                <p>Avenue d'Auderghem 10</p>
                <p>1040 Brusseles, Belgium</p>
            </div>
            <div class="col-lg-3">
                <p>Stay in touch with us</p>
                <ul>
                    <li><a href="#"><i class="fa-brands fa-twitter"></i></a></li>
                    <li><a href="#"><i class="fa-brands fa-pinterest-p"></i></a></li>
                    <li><a href="#"><i class="fa-brands fa-facebook-f"></i></a></li>
                    <li><a href="#"><i class="fa-brands fa-linkedin-in"></i></a></li>
                </ul>
            </div>
        </div>
    </div>
  </footer>
</template>

<script>
export default {
    name: 'BaseFooter' 
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/mixins.scss';
    footer{
        background-color: #C0E1CF;
        padding: var(--padding-section);
        p{
            margin-bottom: .625rem;
        }
        ul{
            @include navBarStyle;
            & a{
                color: inherit;
            }
        }    
    }
</style>