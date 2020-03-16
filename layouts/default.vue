<template>
  <div id="top">
    <scroll-top />
    <wip-navbar />
    <nuxt />
    <wip-footer />
  </div>
</template>

<script>
import WipNavbar from '~/components/WipNavbar'
import WipFooter from '~/components/WipFooter'
import ScrollTop from '~/components/ScrollTop'

export default {
  components: {
    WipNavbar,
    WipFooter,
    ScrollTop
  },

  data() {
    return {
      show: false
    }
  }
}
</script>

<style lang="scss">
.scroll-up {
  position: fixed;
  bottom: 30px;
  right: 30px;
  z-index: 99;
}

@media (max-width: 767px) {
  .scroll-up {
    display: none;
  }
}
</style>
