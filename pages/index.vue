<template>
  <div>
    <hero-home></hero-home>
    <estrategy></estrategy>
    <objetives></objetives>
    <services></services>
    <contact></contact>
  </div>
</template>

<script>
import HeroHome from '~/components/home/Hero'
import Estrategy from '~/components/home/Estrategy'
import Objetives from '~/components/home/Objetives'
import Services from '~/components/home/Services'
import Contact from '~/components/Contact'

export default {
  components: {
    HeroHome,
    Estrategy,
    Objetives,
    Services,
    Contact
  }
}
</script>
