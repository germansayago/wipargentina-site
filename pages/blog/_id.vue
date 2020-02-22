<template>
  <div class="container">
    <h1>Blog</h1>
    <h3>{{ post.title }}</h3>
    <p>{{ post.content }}</p>
  </div>
</template>

<script>
export default {
  name: 'Blog',

  data() {
    return {
      id: this.$route.params.id,
      posts: [
        {
          id: 'post1',
          title: 'Titulo del post 1',
          content: 'Contenido del post 1'
        },
        {
          id: 'post2',
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
