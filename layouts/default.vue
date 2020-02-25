<template>
  <div class="main">
    <wip-navbar />
    <nuxt class="wrapper" />
    <wip-footer />
  </div>
</template>

<script>
import WipNavbar from '~/components/Wip-Navbar'
import WipFooter from '~/components/Wip-Footer'
export default {
  components: {
    WipNavbar,
    WipFooter
  },

  data() {
    return {
      show: false
    }
  }
}
</script>
