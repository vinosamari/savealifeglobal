<template>
  <div>
    <navbar></navbar>
    <Nuxt />
    <my-footer></my-footer>
  </div>
</template>

<script>
import MyFooter from "~/components/MyFooter.vue";
import Navbar from "~/components/Navbar.vue";
export default {
  components: { Navbar, MyFooter },
};
</script>

<style scoped>
</style>