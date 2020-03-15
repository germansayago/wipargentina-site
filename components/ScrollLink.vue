<template>
  <a :href="href" @click.prevent="scroll">
    <slot></slot>
  </a>
</template>

<script>
export default {
  props: {
    href: {
      type: String,
      required: true
    }
  },

  methods: {
    scroll() {
      document
        .querySelector(this.href)
        .scrollIntoView({ top: 100, behavior: 'smooth' })
    }
  }
}
</script>
