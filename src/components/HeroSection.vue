<script setup>
  const title = 'Promote Your Bussiness With <span>Baseland</span>'
  const subTitle = 'We are team of talented designers making websites with Bootstrap'
  const heroImage = '../img/hero-img.png'
</script>

<template>

<section id="hero">
    <div class="container">
      <div class="row justify-content-between">
        <div class="col-lg-7 pt-5 pt-lg-0 order-2 order-lg-1 d-flex align-items-center">
          <div data-aos="zoom-out">
            <h1 v-html="title"></h1>
            <h2>{{ subTitle }}</h2>
            <div class="text-center text-lg-start">
              <a href="#about" class="btn-get-started scrollto">Get Started</a>
            </div>
          </div>
        </div>
        <div class="col-lg-4 order-1 order-lg-2 hero-img" data-aos="zoom-out" data-aos-delay="300">
          <img v-bind:src="heroImage" class="img-fluid animated" alt="">
        </div>
      </div>
    </div>

  </section>

</template>

<style scoped>
  #hero{
    height: 800px;
  }
</style>