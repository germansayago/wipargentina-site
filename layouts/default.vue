<template>
  <div>
    <wip-navbar />
    <nuxt />
    <wip-footer />
  </div>
</template>

<script>
import WipNavbar from '~/components/WipNavbar'
import WipFooter from '~/components/WipFooter'
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
