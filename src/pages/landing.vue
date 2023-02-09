<template>
  <nav-bar />
  <header-component />
  <about-us />
  <blog-area />
  <work-area />
  <services-area />
  <portfolio-area />
  <contact-us />
  <footer-component />
</template>

<script>
import NavBar from '@/components/layout/NavBar.vue'
import HeaderComponent from '@/components/layout/HeaderComponent.vue'
import AboutUs from '@/components/AboutUs.vue'
import BlogArea from '@/components/BlogArea.vue'
import WorkArea from '@/components/WorkArea.vue'
import ServicesArea from '@/components/ServicesArea.vue'
import PortfolioArea from '@/components/PortfolioArea.vue'
import ContactUs from '@/components/ContactUs.vue'
import FooterComponent from '@/components/layout/FooterComponent.vue'
export default {
  components: { NavBar, HeaderComponent, AboutUs, BlogArea, WorkArea, ServicesArea, PortfolioArea, ContactUs, FooterComponent },
    name: 'landing-page'
}
</script>

<style>

</style>