<template>
  <div>
    <hero-home />
    <beneficies />
  </div>
</template>

<script>
import HeroHome from '~/components/home/Hero'
import Beneficies from '~/components/home/Beneficies'

export default {
  components: {
    HeroHome,
    Beneficies
  }
}
</script>
