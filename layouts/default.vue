<template>
  <div>
  <Navigation />
  <div class="content">
    <nuxt />
  </div>
  </div>
</template>

<script>
import Navigation from "../components/Navigation";
export default {
  head() {
    return {
      link: [
        {
          rel: "stylesheet",
          href: "https://fonts.googleapis.com/css?family=Oswald&display=swap"
        }
      ]
    };
  },
  components: {
    Navigation
  }
};
</script>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  background: #2d3436;
  color: whitesmoke;
  font-family: Arial, Helvetica, sans-serif;
}

.content {
  padding: 2rem;
}

</style>
