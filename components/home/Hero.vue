<template>
  <div class="hero">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-10 col-lg-8">
          <h1
            class="display-1"
            data-aos="zoom-in"
            data-aos-delay="50"
            data-aos-once="true"
          >
            Escalemos tu negocio a su máximo potencial
          </h1>
          <h4 data-aos="fade-up" data-aos-delay="400" data-aos-once="true">
            Construimos estrategias digitales de alto valor, claves para el
            futuro de tu negocio en internet.
          </h4>
          <a
            v-scroll-to="{ el: '#estrategy', offset: -50 }"
            href="#"
            class="btn btn-outline-light text-uppercase"
            data-aos="fade-up"
            data-aos-delay="800"
            data-aos-once="true"
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
