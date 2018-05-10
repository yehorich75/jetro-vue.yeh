<template lang="pug">

  div
    .header
      .header__logo Jetro
      nav.header__nav
        router-link(to="/") Home
        router-link(to="post") Post
    slot
    h1 I am footer

</template>

<script>
export default {
  name: 'Layout'
}
</script>

<style>

.header
  border-bottom: 100px solid #f1ad9c

</style>