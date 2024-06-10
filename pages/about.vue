<template>
<div class="about">
  <h1>About us</h1>
  <p>Welcome to out website</p>
  <nuxt-link to="/">HOME</nuxt-link>
</div>
</template>

<script lang="ts">
export default {
  name: 'AboutPage'
}
</script>

<style scoped lang="less">
h1 {
  font-size: 1.5rem;
}

p {
  color: grey;
}
</style>