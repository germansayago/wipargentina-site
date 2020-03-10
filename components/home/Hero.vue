<template>
  <div class="hero">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-8">
          <h1 class="display-1">
            Escalemos tu negocio a su máximo potencial
          </h1>
          <h4>
            From ads that dance or sing to MTV-like commercials, online
            advertisers are now using a new type of technology.
          </h4>
          <scroll-link href="#beneficies" class="btn btn-outline-light"
            >¡DALE!</scroll-link
          >
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import ScrollLink from '~/components/ScrollLink'

export default {
  name: 'HeroHome',

  components: {
    ScrollLink
  }
}
</script>
