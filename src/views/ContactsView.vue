<template>
    <section class="content py-5" id="contact">
        <div class="container-lg py-4">
            <div class="row justify-content-center">
                <div class="col-lg-8">
                    <div class="section-title text-center">
                        <h1 class="fw-bold mb-5">Contact Me</h1>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="container">
                    <div class="row d-flex flex-column flex-md-row">
                        <div class="col-5">
                            <div class="contact-item d-flex">
                                <div class="icon fs-4 text-info">
                                    <i class="bi bi-envelope-fill"></i>
                                </div>
                                <div class="text ms-3">
                                    <h3 class="fs-5">Email</h3>
                                    <p class="text-muted">sogeyanaluntu@gmail.com</p>
                                </div>
                            </div>
                            <div class="contact-item d-flex">
                                <div class="icon fs-4 text-info">
                                    <i class="bi bi-phone"></i>
                                </div>
                                <div class="text ms-3">
                                    <h3 class="fs-5">Phone</h3>
                                    <p class="text-muted">067 826 7299</p>
                                </div>
                            </div>
                            <div class="contact-item d-flex">
                                <div class="icon fs-4 text-info">
                                    <i class="bi bi-geo-alt-fill"></i>
                                </div>
                                <div class="text ms-3">
                                    <h3 class="fs-5">Location</h3>
                                    <p class="text-muted">30 Holst Street, Delft South</p>
                                </div>
                            </div>
                        </div>
                        <div class="col-7">
                            <div class="contact form">
                                <form action="https://formspree.io/f/xvoyvygp" method="POST">
                                    <div class="row">
                                        <div class="col-lg-6 mb-4">
                                            <input type="text" id="name" name="message" placeholder="Your Name" class="form-control form-control-lg"  required>
                                        </div>
                                        <div class="col-lg-6 mb-4">
                                        <input type="email" id="email" name="message" placeholder="Your Email" class="form-control form-control-lg border-0"  required>
                                        </div>
                                    </div>
                                    <div class="row">
                                        <div class="col-lg-12 mb-4">
                                            <input type="text" id="subject" name="message" placeholder="Subject" class="form-control form-control-lg border-0"  required>
                                        </div>
                                    </div>
                                    <div class="row">
                                        <div class="col-lg mb-4">
                                            i<textarea id="message" name="message" placeholder="Your message" class="form-control form-control-lg border-0"  ></textarea>
                                        </div>
                                    </div>                                  
                                    <div class="row">
                                        <div class="col-lg-12">
                                            <button type="submit" class="btn btn-info px-3">Send message</button>
                                        </div>
                                    </div>
                                </form>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        name: 'contacts'
    }
</script>

<style>

</style>