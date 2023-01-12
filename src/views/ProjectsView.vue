<template>
    <div>
        <section class="projects py-5" id="projects">
            <div class="container-lg py-4">
                <div class="row justify-content-center">
                    <div class="col-lg-8">
                        <div class="section-title text-center">
                            <h1 class="fw-bold mb-5">Latest Projects</h1>
                        </div>
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-6 col-lg-4">
                        <div class="projects-item"></div>
                        <img src="https://i.postimg.cc/Fzjrgc0c/Luffy-Flip-card-final.png" class="w-100 img-thumbnail" alt="projects-item">
                        <h2 class="text-capitalized fs-5 my-2">Flip card</h2>
                        <p class="mb4"><a href="https://silver-eclair-a67fc6.netlify.app/" target="_blank" class="text-info text-decoration-none">Live Demo</a></p>
                    </div>
                    <div class="col-md-6 col-lg-4">
                        <div class="projects-item"></div>
                        <img src="https://i.postimg.cc/nz1y2kCv/Screenshot-2022-11-01-090450.png" class="w-100 img-thumbnail" alt="projects-item">
                        <h2 class="text-capitalized fs-5 my-2">E-commerce Site</h2>
                        <p class="mb4"><a href="https://manakixiv.netlify.app/" target="_blank" class="text-info text-decoration-none">Live Demo</a></p>
                    </div>
                    <div class="col-md-6 col-lg-4">
                        <div class="projects-item"></div>
                        <img src="https://i.postimg.cc/MHmpqYxz/portfolio.png" class="w-100 img-thumbnail" alt="projects-item">
                        <h2 class="text-capitalized fs-5 my-2">Bootstrap/CSS/HTML Portfolio</h2>
                        <p class="mb4"><a href="https://luntu-portfolio.netlify.app/" target="_blank"  class="text-info text-decoration-none">Live Demo</a></p>
                    </div>
                    <div class="col-md-6 col-lg-4">
                        <div class="projects-item"></div>
                        <img src="https://i.postimg.cc/FsmnHcCS/Simple-Website.png" class="w-100 img-thumbnail" alt="projects-item">
                        <h2 class="text-capitalized fs-5 my-2">Simple Website</h2>
                        <p class="mb4"><a href="https://2ndweekrevision.netlify.app/" target="_blank"  class="text-info text-decoration-none">Live Demo</a></p>
                    </div>
                </div>
            </div>
        </section>
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
                }
            ]
        }
    }
}
</script>
<style lang="">
    
</style>