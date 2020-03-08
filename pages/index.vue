<template>
  <div>
    <hero-home />
    <beneficies id="beneficies" />
    <estrategy />
    <contact />
  </div>
</template>

<script>
import HeroHome from '~/components/home/Hero'
import Beneficies from '~/components/home/Beneficies'
import Estrategy from '~/components/home/Estrategy'
import Contact from '~/components/Contact'

export default {
  components: {
    HeroHome,
    Beneficies,
    Estrategy,
    Contact
  }
}
</script>
