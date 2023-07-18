<script setup>
  const title = 'Contact'
  const subTitle = 'Contact Us'
  const address_head = 'Location:'
  const address = 'A108 Adam Street, New York, NY 535022'
  const email_text = 'Email:'
  const email_no = 'Email:mdksaiful12@gmail.com'
  const number = '01717800008'
  const phone_text = 'Call:'
  const phone_no = '+1 5589 55488 550'
  const mail_loading = '..loading'
  const mail_success = 'Your message has been sent. Thank you!'
  const send_msg = 'Send Message'
</script>

<template>
  <section id="contact" class="contact">
    <div class="container">

      <div class="section-title" data-aos="fade-up">
        <h2>{{ title }}</h2>
        <p>{{ subTitle }}</p>
      </div>

      <div class="row">

        <div class="col-lg-4" data-aos="fade-right" data-aos-delay="100">
          <div class="info">
            <div class="address">
              <i class="bi bi-geo-alt"></i>
              <h4>{{address_head}}</h4>
              <p>{{ address }}</p>
            </div>

            <div class="email">
              <i class="bi bi-envelope"></i>
              <h4>{{ email_text }}:</h4>
              <p>{{ email_no }}</p>
            </div>

            <div class="phone">
              <i class="bi bi-phone"></i>
              <h4>{{ phone_text }}</h4>
              <p>{{phone_no}}</p>
            </div>

          </div>

        </div>

        <div class="col-lg-8 mt-5 mt-lg-0" data-aos="fade-left" data-aos-delay="200">

          <form action="forms/contact.php" method="post" role="form" class="php-email-form">
            <div class="row">
              <div class="col-md-6 form-group">
                <input type="text" name="name" class="form-control" id="name" placeholder="Your Name" required>
              </div>
              <div class="col-md-6 form-group mt-3 mt-md-0">
                <input type="email" class="form-control" name="email" id="email" placeholder="Your Email" required>
              </div>
            </div>
            <div class="form-group mt-3">
              <input type="text" class="form-control" name="subject" id="subject" placeholder="Subject" required>
            </div>
            <div class="form-group mt-3">
              <textarea class="form-control" name="message" rows="5" placeholder="Message" required></textarea>
            </div>
            <div class="my-3">
              <div class="loading">{{ mail_loading }}</div>
              <div class="error-message"></div>
              <div class="sent-message">{{mail_success}}</div>
            </div>
            <div class="text-center"><button type="submit">{{send_msg}}</button></div>
          </form>

        </div>

      </div>

    </div>
  </section>

</template>

<style scoped>

</style>