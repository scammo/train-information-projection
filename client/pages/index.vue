<template>
  <section class="container">
    <h1 class="title">Train-Projection</h1>
    <h2 class="subtitle">a #DBhackathon project</h2>
    <nuxt-link to="/projection">zur Projektion</nuxt-link>
  </section>
</template>

<script>
export default {
}
</script>

<style>
.container {
  min-height: 100vh;

  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;

  text-align: center;
}

.title {
  font-size: 4em;
}
.subtitle {
  font-weight: 400;
}
</style>
