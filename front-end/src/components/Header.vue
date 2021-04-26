<template>
  <div class="header">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">

      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item">
            <router-link to="/" class="headerbutton" tag="button">Home</router-link>
          </li>
          <li class="nav-item">
            <!-- <router-link class ="header-link" to="/Apply">Apply</router-link> -->
            <router-link to="/Apply" class="headerbutton" tag="button">Apply</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/Portfolio" class="headerbutton" tag="button">Portfolio</router-link>
          </li>
          <!-- <li class="nav-item">
            <a class="nav-link" href="html/team.html">Team</a>
          </li> -->
          <!-- <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
              Products
            </a>
            <div class="dropdown-menu" aria-labelledby="navbarDropdown">
              <a class="dropdown-item" href="">Fake Plants</a>
              <a class="dropdown-item" href="">Real Plants</a>
              <a class="dropdown-item" href="">Accessories</a>
            </div>
          </li> -->

        </ul>
      </div>
      <router-link to="/">
        <img class="logo" src="../assets/logo.svg" />
      </router-link>

    </nav>
  </div>
</template>

<script>
export default {
  name: 'Header',
  components: {

  }
}
</script>

<style>
.logo {
}

.nav-item {
  font-size: 25px;
  padding: 7.5px;
}

.header-link,
.header-link:active {
  color: blue;
}

.header-link:hover,
.header-link:hover:active {
  color: #86724E;
}

.headerbutton,
.headerbutton:active {
  width: 125px;
  border: none;
  color: white;
  border-radius: 20px;
  background-color: #0000FF;
  padding: 10px 15px;
  text-align: center;
  text-decoration: none;
  outline: 0 !important;
}

.headerbutton:hover,
.headerbutton:active:hover {
  cursor: pointer;
  background-color: #8B7752;
  color: white;
}

</style>
