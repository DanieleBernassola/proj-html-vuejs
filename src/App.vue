<script>
import AppHeader from "./components/AppHeader.vue";
import AppFooter from "./components/AppFooter.vue";
export default {
  name: "App",
  data() {
    return {};
  },
  components: {
    AppHeader,
    AppFooter,
  },
  methods: {},
};
</script>
<template>
  <app-header></app-header>
  <router-view></router-view>
  <app-footer></app-footer>
</template>
<style scoped lang="scss"></style>
