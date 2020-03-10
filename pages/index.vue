<template>
  <div>
    <hero-home></hero-home>
    <beneficies id="beneficies"></beneficies>
    <estrategy></estrategy>
    <services></services>
    <contact></contact>
  </div>
</template>

<script>
import HeroHome from '~/components/home/Hero'
import Beneficies from '~/components/home/Beneficies'
import Estrategy from '~/components/home/Estrategy'
import Services from '~/components/home/Services'
import Contact from '~/components/Contact'

export default {
  components: {
    HeroHome,
    Beneficies,
    Estrategy,
    Services,
    Contact
  }
}
</script>
