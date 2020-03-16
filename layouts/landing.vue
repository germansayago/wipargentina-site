<template>
  <div id="top" class="landing">
    <scroll-top />
    <landing-navbar></landing-navbar>
    <nuxt />
  </div>
</template>

<script>
import LandingNavbar from '~/components/landing/LandingNavbar'
import ScrollTop from '~/components/ScrollTop'
export default {
  components: {
    LandingNavbar,
    ScrollTop
  }
}
</script>
