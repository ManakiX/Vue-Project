<template>
    <nav id="nav" class="navbar bg-light sticky-top shadow-sm">
        <div class="container-lg">
          <img class="logo" src="../assets/pngegg.png" alt="logo" width="30" height="30px" >
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
              <li><router-link to ="/testimonials">Testimonials</router-link></li>
              <li><router-link to ="/socials">Socials</router-link></li>
              <li><router-link to ="/education">Education</router-link></li>
              <li><router-link to ="/Resume">Resume</router-link></li>
            </ul>
          </div>
        </div>
      </nav>
</template>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
  }
  
  nav {
    padding: 30px;
  }
  
  nav a {
    font-weight: bold;
    color: #2c3e50;
  }
  
  nav a.router-link-exact-active {
    color: purple;
  }
  .dropdown-menu{
    padding: 0.25rem
  }
.dropdown-menu :hover{
    background-color: #D3D3D3;
}
</style>

<script>

</script>