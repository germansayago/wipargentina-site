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
        <div class="navbar-nav navbar-social ml-auto">
          <!-- <a href="" class="nav-link"
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
          ></a> -->
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
        </div>
      </div>
    </div>
  </nav>
</template>
