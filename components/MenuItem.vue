<template>
  <nuxt-link :to="href">
    <img :src="src" alt width="32px" />
    <span class="label">{{ label }}</span>
  </nuxt-link>
</template>

<script>
export default {
  props: {
    href: {
      type: String,
      required: true,
    },
    label: {
      type: String,
      required: true,
    },
    src: {
      type: String,
      required: true,
    },
  },
}
</script>

<style>
a {
  display: flex;
  align-items: center;
  color: #eefbfb;
  padding: 8px;
}

.label {
  margin-left: 8px;
}

@media only screen and (max-width: 600px) {
  .label {
    display: none;
  }
}
</style>
