<template>
  <div>
    <hero-services />
    <div class="section section-small">
      <div class="container">
        <h1>Servicios</h1>
      </div>
    </div>
  </div>
</template>

<script>
import HeroServices from '~/components/services/HeroServices'

export default {
  name: 'Services',

  components: {
    HeroServices
  }
}
</script>
