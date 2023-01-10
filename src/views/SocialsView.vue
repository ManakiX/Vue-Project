<template>
    <div class="container">
        <div class="avatar">
            <img src="https://i.postimg.cc/4yL9TCRv/DSC-3496.jpg" alt="Luntu" width="100%" height="100%">
        </div>
        <div class="content">
          <h1 id="soc">My Socials</h1>
          <p>Follow me on:</p>
          <p>
            <span><a href="https://twitter.com/LuntuAS/" target="_blank"><i class="bi bi-twitter"></i></a></span>
            <span><a href="https://github.com/manakix/" target="_blank"><i class="bi bi-github"></i></a></span>
            <span><a href="https://https://www.instagram.com/lukhanyisonk/" target="_blank"><i class="bi bi-instagram"></i></a></span>
            <span><a href="https://www.facebook.com/lukhanyiso.nk" target="_blank"><i class="bi bi-facebook"></i></a></span>
          </p>
        </div>
      </div>

</template>

<script>

</script>

<style scoped>
body, html {
    height: 90%;
    margin: 0;
    padding: 0;
    font-family: 'Helvetica', sans-serif;
  }

  #testimonial {
    background-image: url(https://i.postimg.cc/HskfnDMD/cool-background.png) ;
    background-size: cover;
  }

  #home {
    background-image: url(https://i.postimg.cc/HskfnDMD/cool-background.png) ;
    background-size: cover;
  }

  .soc {
    font-size: 24px;
    margin: 10px 0 0 0;
    font-weight: lighter;
    text-transform: uppercase;
    color: #eeeeee;
  }
  
  p {
    font-size: 12px;
    font-weight: light;
    color: #333333;
  }
  
  span a {
    font-size: 18px;
    color: #cccccc;
    text-decoration: none;
    margin: 0 10px;
    transition: all 0.4s ease-in-out;
  }
  
  @keyframes float {
    0% {
      box-shadow: 0 5px 15px 0px rgba(0,0,0,0.6);
      transform: translatey(0px);
    }
    50% {
      box-shadow: 0 25px 15px 0px rgba(0,0,0,0.2);
      transform: translatey(-20px);
    }
    100% {
      box-shadow: 0 5px 15px 0px rgba(0,0,0,0.6);
      transform: translatey(0px);
    }
  }
  
  .container {
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  
  .avatar {
    width: 150px;
    height: 150px;
    box-sizing: border-box;
    border: 5px white solid;
    border-radius: 50%;
    overflow: hidden;
    box-shadow: 0 5px 15px 0px rgba(0,0,0,0.6);
    transform: translatey(0px);
    animation: float 6s ease-in-out infinite;
  }
  
  .content {
    width: 100%;
    max-width: 600px;
    padding: 20px 40px;
    box-sizing: border-box;
    text-align: center;
  }

</style>