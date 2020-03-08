<template>
  <div>
    <hero-blog />
    <section class="section">
      <div class="container">
        <h1>Post {{ post.id }}</h1>
        <h3>{{ post.title }}</h3>
        <p>{{ post.content }}</p>
        <nuxt-link to="/blog" class="btn btn-outline-secondary"
          >volver</nuxt-link
        >
      </div>
    </section>
  </div>
</template>

<script>
import HeroBlog from '~/components/blog/HeroBlog'
export default {
  name: 'Blog',

  components: {
    HeroBlog
  },

  data() {
    return {
      id: this.$route.params.id,
      posts: [
        {
          id: '1',
          title: 'Titulo del post 1',
          content: 'Contenido del post 1'
        },
        {
          id: '2',
          title: 'Titulo del post 2',
          content: 'Contenido del post 2'
        }
      ]
    }
  },

  computed: {
    post() {
      return this.posts.find((post) => post.id === this.id)
    }
  }
}
</script>
