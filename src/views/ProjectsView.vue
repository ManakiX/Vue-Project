<template>
    <div>
        <div v-for="project in projectsArray" :key="projects">
            <div class="card" style="width: 18rem;">
                <img :src=project.projectImage class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">{{project.projectName}}</h5>
                  <a :href=project.demoLink class="btn btn-primary">Demo</a>
                </div>
              </div>
        </div>
    </div>
</template>
<script>

export default {
    name: 'projects',
    data(){
        return{
            projectsArray: [
                {
                    projectName: "Flip-card",
                    projectImage: "https://i.postimg.cc/Fzjrgc0c/Luffy-Flip-card-final.png",
                    demoLink: "https://silver-eclair-a67fc6.netlify.app/",
                },
                {
                    projectName: "E-commerce Site",
                    projectImage: "https://i.postimg.cc/nz1y2kCv/Screenshot-2022-11-01-090450.png",
                    demoLink:"https://manakixiv.netlify.app/",
                },
                {
                    projectName: "Bootstrap/CSS/HTML Portfolio",
                    projectImage: "https://i.postimg.cc/MHmpqYxz/portfolio.png",
                    demoLink:"https://luntu-portfolio.netlify.app/",
                },
                {
                    projectName: "Simple Website",
                    projectImage: "https://i.postimg.cc/FsmnHcCS/Simple-Website.png",
                    demoLink:"https://2ndweekrevision.netlify.app/",
                },
                {
                    projectName: "Calculator",
                    projectImage: "https://i.postimg.cc/gcZ67Tnz/Calculator.jpg",
                    demoLink:"https://luntucalculator.netlify.app/",
                }
            ]
        }
    }
}
</script>
<style lang="">
    
</style>