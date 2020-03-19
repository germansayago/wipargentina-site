<template>
  <div>
    <hero-home></hero-home>
    <estrategy></estrategy>
    <call-to-action></call-to-action>
    <objetives></objetives>
    <services></services>
    <contact></contact>
  </div>
</template>

<script>
import HeroHome from '~/components/home/Hero'
import Estrategy from '~/components/home/Estrategy'
import CallToAction from '~/components/home/CallToAction'
import Objetives from '~/components/home/Objetives'
import Services from '~/components/home/Services'
import Contact from '~/components/Contact'

export default {
  components: {
    HeroHome,
    Estrategy,
    CallToAction,
    Objetives,
    Services,
    Contact
  }
}
</script>
