<script setup>
const title = 'Grat Application Ever'
const description = 'Lorem ipsum dolor sit amet, consectetur adipiing elit, sed do eiusmod tempor incididunt ut labore et laborused sed do eiusmod tempor incididunt ut labore et laborused.'
const about11Title = 'Easy to Costomize'
const about1Description = 'Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry s standard dummy text ever since the 1500s'

const about21Title = 'Extreme Security'
const about2Description = 'Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry s standard dummy text ever since the 1500s'

const about31Title = 'Customer Support'
const about3Description = 'Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry s standard dummy text ever since the 1500s'
</script>

<template>

  <section id="about" class="about">
    <div class="container-fluid">

      <div class="row">
        <div class="col-xl-5 col-lg-6 video-box d-flex justify-content-center align-items-stretch" data-aos="fade-right">

        </div>

        <div class="col-xl-7 col-lg-6 icon-boxes d-flex flex-column align-items-stretch justify-content-center py-5 px-lg-5" data-aos="fade-left">
          <h3>{{ title }}</h3>
          <p>{{ description }}</p>

          <div class="icon-box" data-aos="zoom-in" data-aos-delay="100">
            <div class="icon"><i class="bx bx-fingerprint"></i></div>
            <h4 class="title"><a href="">{{ about11Title }}</a></h4>
            <p class="description">{{ about1Description }}</p>
          </div>

          <div class="icon-box" data-aos="zoom-in" data-aos-delay="200">
            <div class="icon"><i class="bx bx-gift"></i></div>
            <h4 class="title"><a href="">{{ about21Title }}</a></h4>
            <p class="description">{{ about2Description }}</p>
          </div>

          <div class="icon-box" data-aos="zoom-in" data-aos-delay="300">
            <div class="icon"><i class="bx bx-atom"></i></div>
            <h4 class="title"><a href="">{{ about31Title }}</a></h4>
            <p class="description">{{ about3Description }}</p>
          </div>

        </div>
      </div>
    </div>
  </section>

</template>

<style>

</style>