<template>
  <div class="hero">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-8">
          <h3 class="display-3">
            Escalemos tu negocio a su máximo potencial
          </h3>
          <h4>
            From ads that dance or sing to MTV-like commercials, online
            advertisers are now using a new type of technology called “rich
            media” to attract consumers.
          </h4>
          <scroll-link href="#beneficies" class="btn btn-secondary"
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

<style lang="scss" scoped>
.hero {
  height: 100vh;
  padding-top: 100px;
  margin-bottom: 120px;
  background-image: url('/hero-bg-wipargentina.jpg');
  background-size: cover;
  background-position: center center;
  background-repeat: no-repeat;
  text-align: center;
  color: white;
  display: flex;
  align-items: center;

  .display-3 {
    font-weight: 500;
    margin-bottom: 30px;
    color: white;
  }

  h4 {
    font-weight: 300;
    line-height: 2.2rem;
    margin-bottom: 50px;
    color: white;
  }

  .btn {
    padding: 12px 76px;
    letter-spacing: 0.2rem;
  }
}

@media screen and (max-width: 991px) {
  .hero {
    .display-3 {
      font-weight: 500;
      margin-bottom: 20px;
      font-size: 2.5rem;
    }

    h4 {
      font-weight: 300;
      line-height: 1.6rem;
      font-size: 1.3rem;
    }

    .btn {
      padding: 12px 76px;
      letter-spacing: 0.2rem;
    }
  }
}
</style>
