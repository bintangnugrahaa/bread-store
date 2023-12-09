<template>
  <Navbar />
  <div>
    <MySwiper />
  </div>
  <div class="container">
    <Home />
  </div>
  <Footer />
</template>

<script>
import Navbar from './components/Navbar.vue'
import MySwiper from '@/components/Slider.vue';
import Home from '@/components/Home.vue';
import Footer from '@/components/Footer.vue';

export default {
  name: 'App',
  components: {
    Navbar,
    MySwiper,
    Home,
    Footer,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
