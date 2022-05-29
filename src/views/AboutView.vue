<template>
  <div class="about">
    <nav-top />
    <div class="flex"></div>
    <h1>This is an about page</h1>
    <h1>[ONPROGRESS]&nbsp;<a href="#/" class="text-blue-500">Kembali</a></h1>
  </div>
</template>
<script>
import NavTop from "@/components/NavTop.vue";
export default {
  name: "AboutView",
  components: {
    NavTop,
  },
};
</script>
<style>
</style>