<template>
  <div id="app">
    <div class="content">
      <div class="main-title">
        <div class="photo"><img src="./assets/ya.jpg"></div>
        <h1>Evgenia Turueva</h1>
        <ul class="links">
          <li>
            <a href="mailto:tindomirel1994@gmail.com">
              <i class="fas fa-envelope"></i>
            </a>
          </li>
          <li>
            <a href="https://github.com/JaneTurueva" target="_blank">
              <i class="fab fa-github"></i>
            </a>
          </li>
          <li>
            <a href="https://linkedin.com/in/evgenia-turueva" target="_blank">
              <i class="fab fa-linkedin"></i>
            </a>
          </li>
          <li>
            <a href="https://t.me/jane_turueva" target="_blank">
              <i class="fab fa-telegram"></i>
          </a>
          </li>
        </ul>
      </div>
    </div>
    <vue-particles color="#fff"></vue-particles>
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

html, body {
  height: 100%;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 100%;
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
.main-title h1 {
  font-size: 60px;
  line-height: 40px;
}
.photo {
  border-radius: 50%;
  overflow: hidden;
  border: 3px solid #fff;

}
.photo img {
  display: block;
  height: 350px;
  width: 350px;
}
.links a{
  color: #ddd;
  font-size: 35px;
  transition: color 0.2s ease;
}
.links a:hover {
  color: #fff;
}
.links li {
  display: inline-block;
  padding: 0 10px;

}
.content {
  display: flex;
  align-items: center;
  height: 100%;
  justify-content: center;
  width: 100%;
}
</style>
