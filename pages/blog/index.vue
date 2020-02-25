<template>
  <div>
    <hero-blog />
    <div class="container">
      <h1>Blog</h1>
      <p>
        <nuxt-link to="/blog/post1">post 1</nuxt-link>
      </p>
      <p>
        <nuxt-link to="/blog/post2">post 2</nuxt-link>
      </p>
    </div>
  </div>
</template>

<script>
import HeroBlog from '~/components/blog/Hero'

export default {
  name: 'Blog',

  components: {
    HeroBlog
  }
}
</script>
