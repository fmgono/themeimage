<template>
  <footer class="tw-opacity-muted tw-flex tw-flex-col xs:tw-flex-row tw-gap-2 tw-text-center tw-items-center">
    <nav class="tw-inline-flex tw-gap-2">
      <a
        class="tw-link tw-link-muted tw-text-lg tw-inline-flex"
        :href="`https://github.com/${APP_GITHUB_USERNAME}`"
        target="_blank"
        rel="noreferrer noopener"
      >
        <icon name="github" />
      </a>
    </nav>
  </footer>
</template>

<script lang="ts" setup>
const yearsFrom = getYearsFrom(2022)
</script>
