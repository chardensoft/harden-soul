<template>
  <div>
    <Header />
    <div class="applypage">
      <div class="apply">
        <h2 class = "title2">APPLY FOR FUNDING</h2>
      </div>
      <form>
        <div class="form-group">
          <label for="exampleFormControlInput1">Email*</label>
          <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
        </div>
        <div class="form-group">
          <label for="exampleFormControlInput1">Phone*</label>
          <input class="form-control" id="exampleFormControlInput1" placeholder="800-000-0000">
        </div>
        <div class="form-group">
          <label for="exampleFormControlTextarea1">Company*</label>
          <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
        </div>
        <div class="form-group">
          <label for="exampleFormControlTextarea1">Tell us about you and your company (the team, founding story, etc)*</label>
          <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
        </div>
      </form>
      <button class="applybutton2" type="button">Apply Now!
      </button>
    </div>
    <Footer />
  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Footer from '@/components/Footer.vue';

export default {
  name: 'Apply',
  components: {
    Header,
    Footer
  }
}
</script>

<style>
.apply {
  width: 100%;
  background-color: #0000FF;
  text-align: center;
}

.title2 {
  color: white;
  padding: 100px;
  font-size: 40px;
}

form {
  padding-top: 50px;
  width: 60%;
  margin: auto;
}

.applybutton2 {
  margin-left: 42.5%;
  width: 175px;
  background-color: #0000FF;
  border: none;
  color: white;
  padding: 12px 0px;
  text-align: center;
  text-decoration: none;
  font-size: 16px;
  border-radius: 20px;
}
</style>
