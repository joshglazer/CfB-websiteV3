<template>
    <nav class="navbar navbar-expand-lg navbar-light">
      <nuxt-link to="/" exact>
        <img src="/images/cfb_logo_full.png" width="100" height="56" class="d-inline-block align-top" alt="Code For Baltimore">
      </nuxt-link>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNavAltMarkup">
        <div class="navbar-nav align-items-center">
          <nuxt-link to="/about" exact>About Us</nuxt-link>
          <nuxt-link to="/get-involved" exact>Get Involved</nuxt-link>
          <a class="nav-item nav-link" href="events.html">Events</a>
          <a class="nav-item nav-link" href="projects.html">Projects</a>
          <a role="button" class="btn btn-outline-primary" target="_blank" href="https://www.codeforamerica.org/donate-to-a-brigade">Donate</a>
        </div>
      </div>
    </nav>
</template>

<script>
export default {
    props: ['page'] 
}
</script>

<style>

</style>