<template>
  <div>
    <nav-bar/>
    <nuxt />
    <site-footer/>
  </div>
</template>
 
<style>

</style>

<script>
import NavBar from '../components/nav'
import SiteFooter from '../components/footer'

export default {
  components: {
    NavBar,
    SiteFooter
  }
}
</script>
