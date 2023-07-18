<script setup>
import HeaderSection from "@/components/HeaderSection.vue";
import AboutSection from "@/components/AboutSection.vue";
import FeatureSection from "@/components/FeatureSection.vue";
import GallerySection from "@/components/GallerySection.vue";
import TeamSection from "@/components/TeamSection.vue";
import ContactSection from "@/components/ContactSection.vue";
import FooterSection from "@/components/FooterSection.vue";
import HeroSection from "@/components/HeroSection.vue";
import CountSection from "@/components/CountSection.vue";
import DetailsSection from "@/components/DetailsSection.vue";
import PricingSection from "@/components/PricingSection.vue";
import FaqSection from "@/components/FaqSection.vue";
import TestimonialSection from "@/components/TestimonialSection.vue";
</script>

<template>

 <HeaderSection/>
  <HeroSection/>

  <main id="main">

<AboutSection/>
<FeatureSection/>
    <CountSection/>
    <DetailsSection/>
<GallerySection/>
<TeamSection/>
    <TestimonialSection/>
    <PricingSection/>
    <FaqSection/>
    <ContactSection/>
      </main>

<FooterSection/>

</template>

<style scoped>

</style>
