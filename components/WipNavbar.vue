<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
    <div class="container">
      <nuxt-link to="/" class="navbar-brand d-lg-none" alt="home">
        <img src="/wip-color.svg" alt="logo" />
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
          <li class="nav-item">
            <a v-scroll-to="{ el: '#top', offset: 0 }" href="#" class="nav-link"
              >Inicio</a
            >
          </li>
          <li class="nav-item">
            <a
              v-scroll-to="{ el: '#beneficies', offset: -50 }"
              href="#"
              class="nav-link"
              >Beneficios</a
            >
          </li>
          <li class="nav-item">
            <a
              v-scroll-to="{ el: '#estrategy', offset: -50 }"
              href="#"
              class="nav-link"
              >Estrategia</a
            >
          </li>
          <li class="nav-item">
            <a
              v-scroll-to="{ el: '#services', offset: -50 }"
              href="#"
              class="nav-link"
              >Servicios</a
            >
          </li>
        </ul>

        <nuxt-link
          to="/"
          class="navbar-brand mx-auto d-none d-lg-block"
          alt="home"
        >
          <img src="/wip-color.svg" alt="logo" />
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
          <a
            v-scroll-to="{ el: '#contact', offset: -50 }"
            href="#"
            class="nav-link"
            ><ion-icon name="mail"></ion-icon
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
