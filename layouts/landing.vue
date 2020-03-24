<template>
  <div id="top" class="landing">
    <landing-navbar></landing-navbar>
    <nuxt />
  </div>
</template>

<script>
import LandingNavbar from '~/components/landing/LandingNavbar'
export default {
  components: {
    LandingNavbar
  }
}
</script>
