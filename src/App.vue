<template>
  <div id="app">
    <app-header />
    <content-area/>
    <app-footer />
  </div>
</template>

<script>
import AppHeader from "./components/header.vue";
import ContentArea from "./components/content.vue";
import AppFooter from "./components/footer.vue";

export default {
  name: "app",
  components: { AppHeader, AppFooter, ContentArea }
};
</script>

<style>
</style>