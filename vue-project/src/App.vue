<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Navbar from './components/Navbar.vue'
import Footer from './components/Footer.vue'
import Home from './views/Home.vue'
import About from './views/AboutMe.vue'
import Works from './views/Works.vue'

</script>

<template>
  <div class="wrapper">
    <Navbar />
      <Home />
      <About />
      <Works />
    <Footer />
  </div>

    <!-- <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/about">About</RouterLink>
  <RouterView /> -->
</template>