<template>
  <body>
    <LandingPage />
  </body>
</template>

<script>
import LandingPage from './pages/landing.vue'

export default {
  components: { LandingPage },
  name: 'App'
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
