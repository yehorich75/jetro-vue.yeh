<template>
  <div>
    <router-link to="/">Home</router-link>
    <router-link to="post">Post</router-link>
    <slot></slot>
    <h1>I am footer</h1>
  </div>
</template>

<script>
export default {
  name: 'Layout'
}
</script>

<style>

</style>