<template>
  <div>
    <Header />
    <div class="home">
      <div class="intro">
        <div class="content">
          <h2 class = "title1">FINDING AND FUNDING THE BEST ENTREPRENEURS IN THE WORLD</h2>
          <p class = "text1"><br>HS is a family-run venture fund focused on empowering early-career entrepreneurs.
            To date, HS has backed <b>12+ startups from first-time entrepreneurs</b>, which have
            collectively gone on to raise over $16M in additional funding.</p>
        </div>
        <div class="image">
          <img class="bulb" src="../assets/bulb.png" />
        </div>
      </div>
      <button class="applybutton" onclick="location.href='/Apply'" type="button">Apply Now!</button>
    </div>
    <Footer />
  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Footer from '@/components/Footer.vue';

export default {
  name: 'Home',
  components: {
    Header,
    Footer
  }
}
</script>

<style>
.home {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.intro {
  display: flex;
  justify-content: space-around;
  width: 80%;
  margin: auto;
  padding-top: 100px;
}

.content {
  padding: 50px;
}

.title1 {
  font-size: 40px;
}

.text1 {
  font-size: 20px;
  line-height: 2;
}

.image {
  padding: 50px;
}

.applybutton {
  margin-left: 13.75%;
  background-color: #0000FF;
  border: none;
  color: white;
  padding: 12px 32px;
  text-align: center;
  text-decoration: none;
  font-size: 16px;
  border-radius: 20px;
}

/* Mobile Styles */
@media only screen and (max-width: 400px) {
}
/* Tablet Styles */
@media only screen and (min-width: 401px) and (max-width: 960px) {
}
/* Desktop Styles */
@media only screen and (min-width: 961px) {
}

</style>
