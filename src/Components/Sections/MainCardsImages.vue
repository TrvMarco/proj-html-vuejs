<template>
  <section class="cards row">
      <div class="col-lg-4 card-container">
        <div class="card-hover">
          <h3>Illustration of novels</h3>
          <p class="italic-font">Illustration</p>
        </div>
        <img src="../../assets/img/h-2-port-img-1.jpg" class="img-fluid" alt="Illustration image">
      </div>
      <div class="col-lg-4 card-container">
        <div class="card-hover">
          <h3>Illustration of novels</h3>
          <p class="italic-font">Illustration</p>
        </div>
        <img src="../../assets/img/h-2-port-img-2.jpg" class="img-fluid" alt="Illustration image">
      </div>
      <div class="col-lg-4 card-container">
        <div class="card-hover">
          <h3>Illustration of novels</h3>
          <p class="italic-font">Illustration</p>
        </div>
        <img src="../../assets/img/h-2-port-img-3.jpg" class="img-fluid" alt="Illustration image">
      </div>
      <div class="col-lg-4 card-container">
        <div class="card-hover">
          <h3>Illustration of novels</h3>
          <p class="italic-font">Illustration</p>
        </div>
        <img src="../../assets/img/h-2-port-img-4.jpg" class="img-fluid" alt="Illustration image">
      </div>
      <div class="col-lg-4 card-container">
        <div class="card-hover">
          <h3>Illustration of novels</h3>
          <p class="italic-font">Illustration</p>
        </div>
        <img src="../../assets/img/h-2-port-img-5.jpg" class="img-fluid" alt="Illustration image">
      </div>
      <div class="col-lg-4 card-container">
        <div class="card-hover">
          <h3>Illustration of novels</h3>
          <p class="italic-font">Illustration</p>
        </div>
        <img src="../../assets/img/h-2-port-img-6.jpg" class="img-fluid" alt="Illustration image">
      </div>
  </section>
</template>

<script>
export default {
    name: 'MainCardsImages'
}
</script>

<style lang="scss" scoped>
  .cards{
    margin-right: 0;
  }

  .card-container{
    position: relative;
    padding: 0;

    &:hover .card-hover{
      display: block;
    }
  }
  
  .card-hover{
    max-width: 70%;
    position: absolute;
    left: 0;
    top: 45%;
    background-color: #fff;
    padding: 1.875rem;
    display: none;
  }


</style>