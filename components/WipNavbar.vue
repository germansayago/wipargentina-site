<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
    <div class="container">
      <nuxt-link to="/" class="navbar-brand d-lg-none">
        <img src="/wip-color.svg" alt="" />
      </nuxt-link>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarContent"
        aria-controls="navbarContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <ion-icon size="large" name="menu-outline"></ion-icon>
      </button>

      <div id="navbarContent" class="collapse navbar-collapse">
        <ul class="navbar-nav">
          <li class="nav-item" :class="{ active: path === 'index' }">
            <nuxt-link to="/" class="nav-link">Inicio</nuxt-link>
          </li>
          <li class="nav-item" :class="{ active: path === 'services' }">
            <nuxt-link to="/services" class="nav-link">Servicios</nuxt-link>
          </li>
          <li class="nav-item" :class="{ active: path === 'blog' }">
            <nuxt-link to="/blog" class="nav-link">Blog</nuxt-link>
          </li>
        </ul>

        <nuxt-link to="/" class="navbar-brand mx-auto d-none d-lg-block">
          <img src="/wip-color.svg" alt="" />
        </nuxt-link>

        <div class="navbar-social">
          <a href="" class="nav-link"
            ><ion-icon name="logo-twitter"></ion-icon
          ></a>
          <a href="" class="nav-link"
            ><ion-icon name="logo-instagram"></ion-icon
          ></a>
          <a href="" class="nav-link"
            ><ion-icon name="logo-facebook"></ion-icon
          ></a>
          <a href="" class="nav-link"
            ><ion-icon name="logo-linkedin"></ion-icon
          ></a>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  computed: {
    path() {
      return this.$route.name
    }
  }
}
</script>
