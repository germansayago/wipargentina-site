<template>
  <div class="hero">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-12">
          <h3 class="display-3">
            Blog
          </h3>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeroBlog'
}
</script>

<style lang="scss" scoped>
.hero {
  height: 400px;
  padding-top: 120px;
  background-image: url('/hero-bg-wipargentina.jpg');
  background-size: cover;
  background-position: center center;
  background-repeat: no-repeat;
  color: white;
  display: flex;
  align-items: center;

  .display-3 {
    font-weight: 500;
    margin-bottom: 30px;
    color: white;
  }
}

@media screen and (max-width: 991px) {
  .hero {
    height: 240px;
    padding-top: 90px;
    .display-3 {
      font-weight: 500;
      margin-bottom: 20px;
      font-size: 2.5rem;
    }
  }
}
</style>
