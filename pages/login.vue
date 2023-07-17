<script setup lang="ts">
definePageMeta({
  layout: 'default',
  middleware: ['app', 'app-check-logout'],
});
useHead({
  title: 'Login',
});
// ----------------------------------------------------------------------------
</script>
<template>
  <div class="">
    <nuxt-link to="/">〇〇アプリ ログイン</nuxt-link>
  </div>
</template>

<style lang="scss" scoped></style>
