<template>
  <section class="contact" id="contact">
        <div class="container mb-5 py-5">
            <div class="row">
                <div class="col-lg-8 text-center mx-auto">
                    <div data-aos="zoom-in">
                        <p class="h5 text-success my-3">Contact Area</p>
                        <p class="h1">CONTACT</p>
                        <hr class="hr-one m-0 mx-auto">
                        <p class="my-3">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsam, error! Vel deleniti nemo qui consequatur.</p>
                    </div>
                </div>
            </div>
             
            
            <form class="contact-form wow fadeInLeft" id="reused_form" action="POST">
                <div class="row my-form">
                    <div class="col-lg-6">
                        <div class="form-floating mt-4">
                            <input name="name" id="name" type="text" class="form-control" placeholder="Your Name*" required="">
                            <label for="name">Your Name</label>
                        </div>
                        <div class="form-floating mt-4">
                            <input name="email" id="email" type="email" class="form-control" placeholder="Your Email*" required="">
                            <label for="email">Email address</label>
                        </div>
                        <div class="form-floating mt-4">
                            <input type="text" class="form-control" name="subject" id="subject" placeholder="Your Subject.." required="">
                            <label for="subject">Your Subject</label>
                        </div>
                    </div>
                    <div class="col-lg-6">
                        <div class="form-floating mt-4">
                            <textarea style="height: 150px" name="comments" id="comments" cols="20" rows="50" class="form-control" placeholder="Your message..."></textarea>
                            <label for="comments">Your message</label>
                        </div>
                        <div class="col-lg-6  mt-4">
                            <button type="submit" class="h2 fw-bold btn btn-success btn-one px-5 py-2"> Send message</button>
                        </div>
                    </div>
                     
                </div> 
                 
            </form>
        </div>
    </section>
</template>

<script>
export default {
    name: 'contact-us'
}
</script>

<style>

</style>