<template>
  <section class="dashboard">
    <h1 class="title">
      Dashboard
    </h1>
  </section>
</template>

<script>
export default {
  layout: 'app',
  data ({ req }) {
    return {
      name: req ? 'server' : 'client'
    }
  },
  head () {
    return {
      title: `About Page (${this.name}-side)`
    }
  }
}
</script>

<style scoped>

</style>
