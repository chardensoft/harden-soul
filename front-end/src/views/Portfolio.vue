<template>
  <div>
    <Header />
    <div class="portfolio">
      <div class="funded">
        <h2 class = "title3">COMPANIES BY FIRST-TIME FOUNDERS WE'VE BACKED</h2>
      </div>

      <div class="companies">
        <div class="company">
          <a class="comp_link" href="https://www.instagram.com/sports.dada/" target="_blank">
            <img class="comp_logo" src="../assets/images/sports.svg" />
          </a>
        </div>
        <div class="company">
          <a class="comp_link" href="https://www.linkedin.com/company/trolleyapp/" target="_blank">
            <img class="comp_logo" src="../assets/images/trolley.svg" />
          </a>
        </div>
        <div class="company">
          <a class="comp_link">
            <img class="comp_logo" src="../assets/images/orca.svg" />
          </a>
        </div>
        <div class="company">
          <a class="comp_link" href="https://thewoodreportxc.com/" target="_blank">
            <img class="comp_logo" src="../assets/images/wr.svg" />
          </a>
          </a>
        </div>
        <div class="company">
          <a class="comp_link" href="https://audios.com/" target="_blank">
            <img class="comp_logo" src="../assets/images/audios.svg" />
          </a>
        </div>
        <div class="company">
          <a class="comp_link" href="https://www.fcf.io/" target="_blank">
            <img class="comp_logo" src="../assets/images/fcf.svg" />
          </a>
        </div>
        <div class="company">
          <a class="comp_link" href="https://www.facebook.com/housetoplights" target="_blank">
            <img class="comp_logo" src="../assets/images/house.svg" />
          </a>
        </div>
        <div class="company">
          <a class="comp_link" href="https://www.vidangel.com/" target="_blank">
            <img class="comp_logo" src="../assets/images/angel.svg" />
          </a>
        </div>
        <div class="company">
          <a class="comp_link" href="https://www.youtube.com/watch?v=A7k7ls9UHNs" target="_blank">
            <img class="comp_logo" src="../assets/images/freelancer.svg" />
          </a>
        </div>
        <div class="company">
          <a class="comp_link" href="https://tuttletwins.com/" target="_blank">
            <img class="comp_logo" src="../assets/images/tuttle.svg" />
          </a>
        </div>
        <div class="company">
          <a class="comp_link" href="https://ensignathletics.org/" target="_blank">
            <img class="comp_logo" src="../assets/images/ea.svg" />
          </a>
        </div>
        <div class="company">
          <a class="comp_link" href="https://www.citystreetstrat.com/" target="_blank">
            <img class="comp_logo" src="../assets/images/css.svg" />
          </a>
        </div>
        <div class="company">
          <a class="comp_link" href="http://www.pottersportsgroup.com/" target="_blank">
            <img class="comp_logo" src="../assets/images/potter.svg" />
          </a>
        </div>
      </div>
    </div>
    <Footer />
  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Footer from '@/components/Footer.vue';

export default {
  name: 'Portfolio',
  components: {
    Header,
    Footer
  }
}
</script>

<style>
.portfolio {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.funded {
  width: 100%;
  background-color: white;
  text-align: center;
}

.title3 {
  color: black;
  padding: 100px;
  font-size: 40px;
}

.companies {
  display: flex;
  justify-content: flex-start;
  width: 80%;
  flex-wrap: wrap;
  margin-left: 13%;
}

.company {
  padding: 25px;
  margin: 25px;
  border: 1px solid gray;
}

.comp_logo {
  width: 250px;
  height: 250px;
}

</style>
