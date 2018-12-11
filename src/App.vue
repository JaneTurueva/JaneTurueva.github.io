<template>
  <div id="app">
      <div class="content">
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
    margin: 0;
  }

  #app {
    align-items: center;
    background-image: url("./assets/background.jpg");
    background-size: cover;
    display: flex;
    height: 100%;
    justify-content: center;
    width: 100%;
  }

  #particles-js {
    width: 100%;
    height: 100%;
    position: absolute;
    top: 0;
    left: 0;
  }

  .content {
    color: #fff;
    position: relative;
    z-index: 999;
    text-align: center;
    font-family: 'Allura', cursive;
  }

  h1 {
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

  a {
    color: #ddd;
    font-size: 35px;
    transition: all 0.2s ease;
    text-shadow: 1px 1px 4px #333;
  }

  a:hover {
    color: #fff;
  }

  .links li {
    display: inline-block;
    padding: 0 10px;

  }

  @media screen and (max-width: 480px) {
    .photo img {
      width: 300px;
      height: 300px;
    }
  }
</style>
