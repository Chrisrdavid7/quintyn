<template>
  <div>
    <Navbar />
    <HeroSection />
    <ServicesSection />
    <PlansSection />
    <FooterSection />
  </div>
</template>

<script setup>
import Navbar from './components/Navbar.vue'
import HeroSection from './components/HeroSection.vue'
import ServicesSection from './components/ServicesSection.vue'
import PlansSection from './components/PlansSection.vue'
import FooterSection from './components/FooterSection.vue'
</script>

<style>
/* Global Reset */
* {
  box-sizing: border-box;
}

html, body {
  margin: 0;
  padding: 0;
  overflow-x: hidden;
  max-width: 100%;
  width: 100%;
  position: relative;
}

</style>
