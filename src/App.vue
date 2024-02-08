<template>

  <HeroSection />
  <AboutSection />
  <BenefitSection />
  <BannerSection />
</template>

<script>
import HeroSection from './components/HeroSection.vue'
import AboutSection from './components/AboutSection.vue'
import BenefitSection from './components/BenefitSection.vue'
import BannerSection from './components/BannerSection.vue'

export default {
  name: 'App',
  components: {
    HeroSection,
    AboutSection,
    BenefitSection,
    BannerSection
  }
}
</script>

<style>
#app {

}
</style>
