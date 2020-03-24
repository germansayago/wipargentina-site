<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
    <div class="container">
      <a v-scroll-to="{ el: '#top' }" href="#" class="navbar-brand d-lg-none"
        ><img src="/wip-color.svg" alt="logo"
      /></a>
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
            <a
              v-scroll-to="{ el: '#estrategy', offset: -50 }"
              href="#"
              class="nav-link"
              >Estrategia</a
            >
          </li>
          <li class="nav-item">
            <a
              v-scroll-to="{ el: '#objetives', offset: -50 }"
              href="#"
              class="nav-link"
              >Objetivos</a
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

        <a
          v-scroll-to="{ el: '#top' }"
          href="#"
          class="navbar-brand mx-auto d-none d-lg-block"
          ><img src="/wip-color.svg" alt="logo"
        /></a>

        <div class="navbar-social">
          <div class="nav-item">
            <a
              href="https://wa.me/5493584112731"
              class="nav-link"
              target="_blank"
              ><ion-icon name="logo-whatsapp"></ion-icon
            ></a>
          </div>
          <div class="nav-item">
            <a
              href="https://www.instagram.com/wipargentina/"
              class="nav-link"
              target="_blank"
              ><ion-icon name="logo-instagram"></ion-icon
            ></a>
          </div>
          <div class="nav-item">
            <a
              href="https://www.facebook.com/wipargentina"
              class="nav-link"
              target="_blank"
              ><ion-icon name="logo-facebook"></ion-icon
            ></a>
          </div>
          <div class="nav-item">
            <a
              href="https://www.linkedin.com/company/wipargentina"
              class="nav-link"
              target="_blank"
              ><ion-icon name="logo-linkedin"></ion-icon
            ></a>
          </div>
          <div class="nav-item">
            <a
              href="https://twitter.com/wipargentina"
              class="nav-link"
              target="_blank"
              ><ion-icon name="logo-twitter"></ion-icon
            ></a>
          </div>
          <div class="nav-item">
            <a
              v-scroll-to="{ el: '#contact', offset: -50 }"
              href="#"
              class="nav-link"
              ><ion-icon name="mail"></ion-icon
            ></a>
          </div>
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
