<template>
 <Navbar/>
  <router-view/>
  <FooterComponent/>
</template>

<script>
import Navbar from './components/NavBar.vue'
import FooterComponent from './components/FooterComponent.vue'
export default {
  components: {
    Navbar,
    FooterComponent
  }
}

</script>

<style>
@import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.3/font/bootstrap-icons.css");;
.home-img img{
    border-radius: 50%;
    height: 22rem;
    width: 22rem;
}
.logo{
    height: 30px;
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
