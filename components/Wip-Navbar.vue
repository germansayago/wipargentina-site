<template>
  <nav
    class="navbar navbar-expand-lg bg-light d-flex justify-content-between py-5"
  >
    <div class="container">
      <div>
        <ul>
          <li>
            <nuxt-link to="/">inicio</nuxt-link>
            <nuxt-link to="/">servicio</nuxt-link>
            <nuxt-link to="/blog">blog</nuxt-link>
            <nuxt-link to="/">contacto</nuxt-link>
          </li>
        </ul>
      </div>
      <div>
        <nuxt-link to="/" class="navbar-brand">WIP!</nuxt-link>
      </div>
      <div>social</div>
    </div>
  </nav>
</template>

<style lang="scss" scoped>
.navbar {
  background-color: rgba(red, 0.5);
}
</style>
