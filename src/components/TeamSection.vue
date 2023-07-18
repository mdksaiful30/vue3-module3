<script setup>
import person from '../data/teamMembers'

const title = 'Our Great Team'
const subTitle = 'Team'

</script>

<template>

  <section id="team" className="team">
    <div className="container">

      <div className="section-title" data-aos="fade-up">
        <h2>{{ subTitle }}</h2>
        <p>{{ title }}</p>
      </div>

      <div className="row" data-aos="fade-left">

        <div className="col-lg-3 col-md-6">
          <div className="member" data-aos="zoom-in" data-aos-delay="100">
            <div className="pic"><img :src="person[0].image" class="img-fluid" alt=""></div>
            <div className="member-info">
              <h4>{{ person[0].name }}</h4>
              <span>{{ person[0].designation }}</span>
              <div className="social">
                <a href="#"><i className="bi bi-twitter"></i></a>
                <a href="#"><i className="bi bi-facebook"></i></a>
                <a href="#"><i className="bi bi-instagram"></i></a>
                <a href="#"><i className="bi bi-linkedin"></i></a>
              </div>
            </div>
          </div>
        </div>

        <div className="col-lg-3 col-md-6">
          <div className="member" data-aos="zoom-in" data-aos-delay="100">
            <div className="pic"><img :src="person[1].image" class="img-fluid" alt=""></div>
            <div className="member-info">
              <h4>{{ person[1].name }}</h4>
              <span>{{ person[1].designation }}</span>
              <div className="social">
                <a href="#"><i className="bi bi-twitter"></i></a>
                <a href="#"><i className="bi bi-facebook"></i></a>
                <a href="#"><i className="bi bi-instagram"></i></a>
                <a href="#"><i className="bi bi-linkedin"></i></a>
              </div>
            </div>
          </div>
        </div>

        <div className="col-lg-3 col-md-6">
          <div className="member" data-aos="zoom-in" data-aos-delay="100">
            <div className="pic"><img :src="person[2].image" class="img-fluid" alt=""></div>
            <div className="member-info">
              <h4>{{ person[2].name }}</h4>
              <span>{{ person[2].designation }}</span>
              <div className="social">
                <a href="#"><i className="bi bi-twitter"></i></a>
                <a href="#"><i className="bi bi-facebook"></i></a>
                <a href="#"><i className="bi bi-instagram"></i></a>
                <a href="#"><i className="bi bi-linkedin"></i></a>
              </div>
            </div>
          </div>
        </div>

        <div className="col-lg-3 col-md-6">
          <div className="member" data-aos="zoom-in" data-aos-delay="100">
            <div className="pic"><img :src="person[3].image" class="img-fluid" alt=""></div>
            <div className="member-info">
              <h4>{{ person[3].name }}</h4>
              <span>{{ person[3].designation }}</span>
              <div className="social">
                <a href="#"><i className="bi bi-twitter"></i></a>
                <a href="#"><i className="bi bi-facebook"></i></a>
                <a href="#"><i className="bi bi-instagram"></i></a>
                <a href="#"><i className="bi bi-linkedin"></i></a>
              </div>
            </div>
          </div>
        </div>

      </div>

    </div>
  </section>

</template>

<style scoped>

</style>



