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

<style lang="sass">

.header
  border-bottom: 100px solid #f1ad9c
  &__logo
    float: left
    font-size: 50px
  &__nav
    float: right
    white-space: nowrap
    font-size: 15px
    text-transform: uppercase
    a 
      text-decoration: none
      padding: 10px
      display: inline-block

</style>