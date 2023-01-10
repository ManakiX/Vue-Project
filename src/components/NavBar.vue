<template>
    <nav id="nav" class="navbar bg-light sticky-top shadow-sm">
        <div class="container-lg">
          <img src="../assets/pngegg.png" alt="logo" width="30" height="30px" >
          <a class="navbar-brand text-black fw-bold fs-4" href="#">RSA</a>
          <div class="dropdown">
            <button class="btn btn-secondary btn-dark px-3" type="button" data-bs-toggle="dropdown" aria-expanded="false">
                <span class="navbar-toggler-icon"></span>
             <i class="fas fa-bars"></i>
        
            </button>
            <ul class="dropdown-menu">
              <li><router-link to ="/">Home</router-link></li>
              <li><router-link to ="/about">About</router-link></li>
              <li><router-link to ="/projects">Projects</router-link></li>
              <li><router-link to ="/contacts">Contacts</router-link></li>
              <li><router-link to ="/testimonials">Testimonials</router-link>></li>
              <li><router-link to ="/socials">Socials</router-link></li>
              <li><router-link to ="/education">Education</router-link></li>
            </ul>
          </div>
        </div>
      </nav>
</template>

<style>
</style>

<script>
</script>