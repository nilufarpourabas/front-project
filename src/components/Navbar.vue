<template>
  <div id="nav">
    <title>Web Developers!</title>

    <div class="sticky-top shadow bg-white p-1 mb-5" style="--bs-bg-opacity: 0.95">
      <nav class="container navbar navbar-expand-lg navbar-light">
        <div class="container-fluid">
          <a class="navbar-brand fs-4" href="#">Web Developers!</a>
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarColor03"
            aria-controls="navbarColor03"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarColor03">
            <ul class="navbar-nav mx-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <router-link class="nav-link active" to="/">Home</router-link>
              </li>
              <li class="nav-item">
                <router-link class="nav-link" to="/About">About</router-link>
              </li>
              <li class="nav-item">
            <router-link class="nav-link" to="/jobs">Jobs</router-link>
              </li>
              <li class="nav-item">
            <!-- <router-link class="nav-link" to="/cards">Cards</router-link> -->
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </div>

    
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style>
</style>

