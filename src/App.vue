<template>
  <div id="app">
    <div class="main-title">
      <h1>Evgenia Turueva</h1>
    </div>
    <vue-particles color="#fff">
    </vue-particles>
  </div>
</template>

<script>
import Vue from 'vue'
import VueParticles from 'vue-particles'
Vue.use(VueParticles)
export default {
  name: 'app',
}

</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
#particles-js {
  background-image: url("./assets/background.jpg");
  width: 100%;
  height: 100%;
  background-size: cover;
  position: absolute;
  top: 0;
  left: 0;
}
.main-title {
  color: #fff;
  position: relative;
  z-index: 999;
  font-family: 'Allura', cursive;
  font-size: 25px;
}

</style>
