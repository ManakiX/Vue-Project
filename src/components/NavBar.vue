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
              <li><router-link to ="/testimonials">Testimonials</router-link></li>
              <li><router-link to ="/socials">Socials</router-link></li>
              <li><router-link to ="/education">Education</router-link></li>
            </ul>
          </div>
        </div>
      </nav>
</template>

<style>
@import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.9.1/font/bootstrap-icons.css");
.home-img img{
    border-radius: 50%;
    height: 22rem;
    width: 22rem;
}
h1{
    color: purple !important;
    font-weight: bold;
}
h2{
    font-size: medium;
}
.btn{
background-color:#EF798A;
}


/* @media screen and (max-width: 1080px) {
    #nav {
        margin: 0px 100px;
    }
} */
.star-widget label{
    font-size: 40px;
    color: grey;
    padding: 10px;
    float: right;
}
.input:not(:checked) ~ label:hover,
.input:not(:checked) ~ label:hover ~label{
    color: red;
}
input {
    box-shadow: 4px 2px 10px 5px rgb(238, 0, 255);
    background-color: black;
}
textarea{
    box-shadow: 4px 2px 10px 5px rgb(238, 0, 255);
    background-color: black
}
body{
    /* background-color:rgba(243, 237, 201, 0.782); */
    background-image: url(https://i.postimg.cc/HskfnDMD/cool-background.png) ;
    background-repeat: no-repeat;
    background-size: cover;
    overflow-x: hidden;
}

  #nav{
    width: auto;
}

.inner {
    overflow: hidden;
}

.inner img{
    transition: all 1.5s ease;
}

.inner:hover img{
    transform: scale(1.5);
}

@media screen  and  (max-width: 1080px) {
    .dropdown-menu {
        top:100% !important;
        left: -100% !important;
    }
} 
.rounded-circle {
    box-sizing: border-box;
    border: 5px white solid;
    border-radius: 50%;
}
</style>

<script>

</script>