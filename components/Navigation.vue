<template>
  <header class="header">
    <h1 class="text-title">Posts App</h1>
    <nav>
      <ul>
        <li>
          <nuxt-link to="/">Home</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/posts">Posts</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/about">About</nuxt-link>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'Navigation'
}
</script>

<style>

.header {
  background: #2c3e50;
  color: #ffffff;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 3rem;
  border-bottom: 1px dotted #2ecc71;
}

.header .text-title {
  font-family: "Oswald";
  font-size: 2rem;
  text-transform: uppercase;
}

.header ul {
  display: flex;
  list-style: none;
}

.header a {
  color: #ffffff;
  background: #2d3436;
  padding: 0.3rem 1rem;
  margin-right: 0.5rem;
  text-decoration: none;
  text-transform: uppercase;
}

.header a:hover {
  background: #2c3e50;
  border: 1px solid #bdc3c7;
}
</style>
