<template>
  <section class="contact" id="Contact">
    <div class="container mx-auto bg-dark mt-5 text-white rounded">
      <div class="row">
        <div class="col p-5">
          <h2>Contact Me</h2>
          <p>Feel free to reach out to me through any of the following methods:</p>
          <form action="#" method="post">
            <div class="mb-3">
              <label for="name" class="form-label">Name</label>
              <input type="text" class="form-control" id="name" required />
            </div>
            <div class="mb-3">
              <label for="email" class="form-label">Email</label>
              <input type="email" class="form-control" id="email" required />
            </div>
            <div class="mb-3">
              <label for="subject" class="form-label">Subject</label>
              <textarea class="form-control" id="subject" rows="1" required></textarea>
            </div>
            <div class="mb-3">
              <label for="message" class="form-label">Message</label>
              <textarea class="form-control" id="message" rows="3" required></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Send Message</button>
          </form>
        </div>
        <div class="d-col p-5">
          <img src="/assets/img/2.png" alt="apa hayo" style="width: 350px;">
          
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ContactSection'
}
</script>

<style scoped>
.contact {
  padding: 50px 200px;
  background-color: #222831;
  color: white;
}
</style>
