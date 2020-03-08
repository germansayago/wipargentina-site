<template>
  <div id="top">
    <scroll-link href="#top" class="btn btn-secondary scroll-up"
      ><ion-icon name="arrow-up-outline"></ion-icon
    ></scroll-link>
    <wip-navbar />
    <nuxt />
    <wip-footer />
  </div>
</template>

<script>
import WipNavbar from '~/components/WipNavbar'
import WipFooter from '~/components/WipFooter'
import ScrollLink from '~/components/ScrollLink'

export default {
  components: {
    WipNavbar,
    WipFooter,
    ScrollLink
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
</style>
