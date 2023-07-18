<script setup>
  const title = 'Gallery'
  const SubTitle = 'Check our Gallery'
  const images = [
    {
      image:'https://images.unsplash.com/photo-1506744038136-46273834b3fb?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80',
      title: 'Water surrounded by trees and mountains...',
      link: 'https://unsplash.com/photos/NRQV-hBF10M',
    },
    {
      image:'https://images.unsplash.com/photo-1532274402911-5a369e4c4bb5?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1170&q=80',
      title: 'Brown wooden dock between lavender flower field...',
      link: 'https://unsplash.com/photos/K2s_YE031CA',
    },
    {
      image:'https://images.unsplash.com/photo-1470770841072-f978cf4d019e?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80',
      title: 'Brown house near body of water...',
      link: 'https://unsplash.com/photos/zAjdgNXsMeg',
    },
    {
      image:'https://www.istockphoto.com/photo/cheerful-beautiful-asian-woman-holding-smartphone-and-shows-ok-sign-on-light-yellow-gm1438065753-478674947?utm_source=unsplash&utm_medium=affiliate&utm_campaign=srp_photos_top&utm_content=https%3A%2F%2Funsplash.com%2Fs%2Fphotos%2Fmobile&utm_term=mobile%3A%3A%3A',
      title: 'Brown house near body of water...',
      link: 'https://unsplash.com/photos/zAjdgNXsMeg',
    },
  ]
  </script>

<template>

  <section id="gallery" class="gallery">
    <div class="container">

      <div class="section-title" data-aos="fade-up">
        <h2>{{ title }}</h2>
        <p>{{ SubTitle }}</p>
      </div>

      <div class="row g-0" data-aos="fade-left">

        <div class="col-lg-3 col-md-4">
          <div class="gallery-item" data-aos="zoom-in" data-aos-delay="100">
            <a :href="images[0].link" class="gallery-lightbox">
              <img :src="images[0].image" alt="" class="img-fluid">
            </a>
          </div>
        </div>

        <div class="col-lg-3 col-md-4">
          <div class="gallery-item" data-aos="zoom-in" data-aos-delay="100">
            <a :href="images[1].link" class="gallery-lightbox">
              <img :src="images[1].image" alt="" class="img-fluid">
            </a>
          </div>
        </div>

        <div class="col-lg-3 col-md-4">
          <div class="gallery-item" data-aos="zoom-in" data-aos-delay="100">
            <a :href="images[2].link" class="gallery-lightbox">
              <img :src="images[2].image" alt="" class="img-fluid">
            </a>
          </div>
        </div>

        <div class="col-lg-3 col-md-4">
          <div class="gallery-item" data-aos="zoom-in" data-aos-delay="100">
            <a :href="images[0].link" class="gallery-lightbox">
              <img :src="images[0].image" alt="" class="img-fluid">
            </a>
          </div>
        </div>

        <div class="col-lg-3 col-md-4">
          <div class="gallery-item" data-aos="zoom-in" data-aos-delay="100">
            <a :href="images[1].link" class="gallery-lightbox">
              <img :src="images[1].image" alt="" class="img-fluid">
            </a>
          </div>
        </div>

        <div class="col-lg-3 col-md-4">
          <div class="gallery-item" data-aos="zoom-in" data-aos-delay="100">
            <a :href="images[2].link" class="gallery-lightbox">
              <img :src="images[2].image" alt="" class="img-fluid">
            </a>
          </div>
        </div>

        <div class="col-lg-3 col-md-4">
          <div class="gallery-item" data-aos="zoom-in" data-aos-delay="100">
            <a :href="images[0].link" class="gallery-lightbox">
              <img :src="images[0].image" alt="" class="img-fluid">
            </a>
          </div>
        </div>

        <div class="col-lg-3 col-md-4">
          <div class="gallery-item" data-aos="zoom-in" data-aos-delay="100">
            <a :href="images[1].link" class="gallery-lightbox">
              <img :src="images[1].image" alt="" class="img-fluid">
            </a>
          </div>
        </div>


      </div>

    </div>
  </section>

</template>

<style scoped>

</style>