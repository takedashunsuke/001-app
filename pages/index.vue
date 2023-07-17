<script setup lang="ts">
definePageMeta({
  layout: 'app',
  middleware: ['app', 'app-check-login'],
});
useHead({
  title: 'Home',
});
const storeApp = useStoreApp();
// ----------------------------------------------------------------------------
</script>
<template>
  <div class="">
    <div class="bg-white">
      <div class="" style="display: flex">
        <nuxt-link color="primary" to="/login" class="ms-auto">logout</nuxt-link>
      </div>
      <test>AAAA</test>
      <div>
        {{ Hoge('fuge') }}
      </div>
    </div>
    <div class="bg-white mt-3">
      <div class="" style="display: flex">
        <button color="primary" class="ms-auto" @click="storeApp.log('')">Log Push</button>
      </div>
    </div>
  </div>
</template>
<style lang="scss" scoped></style>
