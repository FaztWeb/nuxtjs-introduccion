<template>
  <h1>Welcome to My first Nuxt App</h1>
</template>

<script>
export default {
  head() {
    return {
      title: "Posts App | Home",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "Website abut tutorials"
        }
      ],
      htmlAttrs: {
        lang: "en"
      }
    };
  }
};
</script>

<style>
</style>
