<template>
    <!-- <div>
    <section id="testimonial">
        <div class="container-lg">
            <div class="row justify-content-center">
                <div class="col-lg-8">
                    <div class="section-title text-center">
                        <h1 class="fw-bold mb-5">Testimonials</h1>
                    </div>
                </div>
            </div>
        </div>
        <br><br><br>
        <div class="row justify-content-evenly">
            <div class="card" style="width: 18rem;">
                <div class="inner">
                    <img src="https://i.postimg.cc/hhWf3RYy/IMG-20221103-WA0005.jpg" class="card-img-top p-5" alt="">
                </div>
                <div class="card-body">
                  <p class="card-text">Jeff Ricardo</p>
                  <p class="test card-text">Luntu is one of a kind, he has ideas you would think are impossible, until he shows you in the idea in it's fullest and you realize, he's a genius.He has a bright future in front of him and he's always willing to learn new types of things to broaden up he's knowledge.
                  </p>
                </div>
            </div>
            <div class="card" style="width: 18rem;">
                <div class="inner">
                    <img src="https://i.postimg.cc/Kz8bHftL/Sakhe.jpg" class="card-img-top p-5" alt="">
                </div>
                <div class="card-body">
                    <p class="card-text">Sakhe Mzolisa</p>
                    <p class="test card-text">Luntu is one of the most honest people you can come across. Very wise beyond his years with bright ideas which could shake the world in a very positive way. A man who is not afraid to live and speak his truth.</p>
                </div>
            </div>
            <div class="card" style="width: 18rem;">
                <div class="inner">
                    <img src="https://i.postimg.cc/13xJQg6X/image.jpg" class="card-img-top p-5" alt="">
                </div>
                <div class="card-body">
                    <p class="card-text">Joel Mukanya</p>
                    <p class="test card-text">Luntu is a very creative, and well-behaved student. He does enjoy working with his classmates and works well on his project.
                        He has gained knowledge of web development, including Bootstrap 5. I will be very delighted to see him get hired as a developer.</p>
                </div>
            </div>
        </div><br><br><br><br>
        <div class="row justify-content-evenly">
            <div class="card col-1" style="width: 18rem;">
                <div class="inner">
                    <img src="https://i.postimg.cc/1zH5cqPj/IMG-3573.jpg" class="card-img-top p-5" alt="">
                </div>
                <div class="card-body">
                    <p class="card-text">Timothy Jennike</p>
                    <p class="test card-text">Luntu is a hard-working guy who can accomplish anything he puts his mind to. He has a very friendly personality which makes it very easy to oproach him. He is very dedicated and committed to any project that he has set for himself. </p>
                </div>
            </div>
            <div class="card col-1" style="width: 18rem;">
                <div class="inner">
                    <img src="https://i.postimg.cc/YSgSPCg1/IMG-20221004-074457-848.jpg" class="card-img-top p-5" alt="Athenkosi Freddie">
                </div>
                <div class="card-body">
                    <p class="card-text">Athenkosi Freddie</p>
                    <p class="test card-text">Luntu is a serious & fun individual who enjoys learning and exploring different things. He enthusiasm into his work allows him to be creative with the littlest of things, and never seems to fail to make the environment quite lively. You won't regret having him as part of your team.</p>
                </div>
            </div>
        </div> -->
        <div v-for="testimonial in testimonialsArray" :key="testimonial">
            <div class="card" style="width: 18rem;">
                <img :src=testimonial.image class="card-img-top" alt="...">
                <div class="card-body">
                  <p class="card-title">{{testimonial.name}}</p>
                  <p class="card-job">{{testimonial.occupation}}</p>
                  <p class="card-text">{{testimonial.testimonial}}</p>
                </div>
              </div>

        </div>
        <footer>
            Copyright &copy;2022
          </footer>
      <!-- https://console.firebase.google.com/project/luntuvueportfolio/overview
      Hosting URL: https://luntuvueportfolio.web.app -->
</template>

<script>
export default {
    name: 'testimonials',
    data(){
        return{
            testimonialsArray: [
    {
        name: "Jeff Ricardo",
        occupation:"Student",
        image:"https://i.postimg.cc/hhWf3RYy/IMG-20221103-WA0005.jpg",
        testimonial:"Luntu is one of a kind, he has ideas you would think are impossible, until he shows you in the idea in it's fullest and you realize, he's a genius.He has a bright future in front of him and he's always willing to learn new types of things to broaden up he's knowledge.",
    },
    {
        name: "Sakhe Mzolisa",
        occupation:"Student",
        image:"https://i.postimg.cc/Kz8bHftL/Sakhe.jpg",
        testimonial:"Luntu is one of the most honest people you can come across. Very wise beyond his years with bright ideas which could shake the world in a very positive way. A man who is not afraid to live and speak his truth.",
    },
    {
        name: "Joel Mukanya",
        occupation:"Lecturer",
        image:"https://i.postimg.cc/13xJQg6X/image.jpg",
        testimonial:"Luntu is a very creative, and well-behaved student. He does enjoy working with his classmates and works well on his project.He has gained knowledge of web development, including Bootstrap 5. I will be very delighted to see him get hired as a developer.",
    },
    {
        name: "Timothy Jennike",
        occupation:"Student",
        image:"https://i.postimg.cc/1zH5cqPj/IMG-3573.jpg",
        testimonial:"Luntu is a hard-working guy who can accomplish anything he puts his mind to. He has a very friendly personality which makes it very easy to approach him. He is very dedicated and committed to any project that he has set for himself.",
    },
    {
        name: "Athenkosi Freddie",
        occupation:"Student",
        image:"https://i.postimg.cc/YSgSPCg1/IMG-20221004-074457-848.jpg",
        testimonial:"Luntu is a serious & fun individual who enjoys learning and exploring different things. He enthusiasm into his work allows him to be creative with the littlest of things, and never seems to fail to make the environment quite lively. You won't regret having him as part of your team.",
    }]
        }
    }
}
</script>


<style scoped>
* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }
</style>