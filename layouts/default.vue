<template>
  <div id="wrapper" class="clearfix">
    <Header />
    <div class="container mt-4">
      <Nuxt />
    </div>
  </div>
</template>

<script>
import Header from "../components/Header";

export default {
  components: {
    Header,
  },
  head() {
    return {
      bodyAttrs: {
        class: "stretched ",
      },
    };
  },
};
</script>

<style>
</style>
