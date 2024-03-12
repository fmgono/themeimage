<template>
  <nav class="tw-flex tw-justify-center sm:tw-justify-start">
    <nuxt-link
      class="tw-mr-5"
      :to="localePath({ name: 'index' })"
    >
      <h3>themeimage</h3>
    </nuxt-link>
  </nav>
</template>

<script setup lang="ts">
const localePath = useLocalePath()
</script>
