<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
    <div class="container">
      <div class="navbar-brand">
        <img src="/wip-color.svg" alt="logo" />
      </div>
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
        <div class="navbar-nav">
          <div class="nav item">
            <nuxt-link to="/" class="nav-link">inicio</nuxt-link>
          </div>
          <div class="nav item">
            <nuxt-link to="/landing/base" class="nav-link">base</nuxt-link>
          </div>
          <div class="nav item">
            <nuxt-link to="/landing/tienda-express" class="nav-link"
              >tienda express</nuxt-link
            >
          </div>
          <div class="nav item">
            <nuxt-link to="/landing/estrategias-y-analiticas" class="nav-link"
              >Estrategia y Analíticas</nuxt-link
            >
          </div>
        </div>
        <ul class="navbar-nav navbar-social ml-auto">
          <li class="nav-item">
            <a href="#" class="nav-link"
              ><ion-icon name="logo-twitter"></ion-icon
            ></a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link"
              ><ion-icon name="logo-instagram"></ion-icon
            ></a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link"
              ><ion-icon name="logo-facebook"></ion-icon
            ></a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link"
              ><ion-icon name="logo-linkedin"></ion-icon
            ></a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
