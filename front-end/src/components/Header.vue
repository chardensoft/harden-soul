<template>
  <div class="header">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">

      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item active">
            <a class="nav-link" href="/">Home</a>
          </li>
          <li class="nav-item active">
            <a class="nav-link" href="/Apply">Apply</a>
          </li>
          <li class="nav-item active">
            <a class="nav-link" href="/Portfolio">Portfolio</a>
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

      <img class="logo" src="../assets/logo.svg" />

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
}
</style>
