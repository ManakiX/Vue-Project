<template>
  <section class="home py-5" id="">
    <div class="container-lg">
      <div class="row min-vh-100 align-items-center align-content-center">
          <div class="col-md-6 mt-5 mt-md-0">
              <div class="home-img text-center">
                  <img src="https://i.postimg.cc/4yL9TCRv/DSC-3496.jpg" class="rounded-circle mw-100" alt="profile img">
              </div>
          </div>
          <div class="col-md-6 mt-5 mt-md-0 order-md-first">
              <div class="home-text">
                  <p class="text mb-1 fs-1">Hello I'm</p>
                  <h1>Aspiring Web Developer</h1>
                  <h2 class="fs-1">Luntu Sogeyana</h2>
                  <router-link to = "/projects" class="btn">My work</router-link>
              </div>
          </div>
      </div>
    </div>
</section>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
