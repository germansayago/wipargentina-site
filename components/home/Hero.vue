<template>
  <div class="hero">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-10 col-lg-8">
          <h1
            class="display-1"
            data-aos="fade-up"
            data-aos-easing="ease"
            data-aos-delay="400"
          >
            Escalemos tu negocio a su máximo potencial
          </h1>
          <h4>
            Construimos estrategias digitales de alto valor, claves para el
            futuro de tu negocio en internet.
          </h4>
          <a
            v-scroll-to="{ el: '#estrategy', offset: -50 }"
            href="#"
            class="btn btn-outline-light text-uppercase"
            >¡Comencemos!</a
          >
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeroHome'
}
</script>
