<template>
  <div>
    <hero-blog />
    <div class="section section-small">
      <div class="container">
        <h1 class="mb-3">Blog</h1>
        <p>
          <nuxt-link to="/blog/1" class="btn btn-outline-secondary"
            >post 1</nuxt-link
          >
        </p>
        <p>
          <nuxt-link to="/blog/2" class="btn btn-outline-secondary"
            >post 2</nuxt-link
          >
        </p>
      </div>
    </div>
  </div>
</template>

<script>
import HeroBlog from '~/components/blog/HeroBlog'

export default {
  name: 'Blog',

  components: {
    HeroBlog
  }
}
</script>
