<template>
  <section class="container">
    <nuxt-link class="button login-button" to="/app">
      Login
    </nuxt-link>
    <img src="../assets/img/logo.png" alt="Nuxt.js Logo" class="logo" />
    <h1 class="title">
      Universal Vue.js Application Framework
    </h1>
    <nuxt-link class="button" to="/about">
      About page
    </nuxt-link>
  </section>
</template>

<style scoped>
.title
{
  margin: 50px 0;
}

.login-button {
  position: absolute;
  top: 20px;
  right: 20px;
}
</style>
