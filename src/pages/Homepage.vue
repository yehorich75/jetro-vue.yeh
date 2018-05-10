<template>
<main-layout>
  <div class="hello">
    <h1 class="singlepost">{{ msg }}</h1>
  </div>
</main-layout>

</template>

<script>
import MainLayout from '@/layout/MainLayout';
export default {
  name: 'Homepage',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components: {
    MainLayout
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="sass">
.singlepost
  background: green

h1, h2
  font-weight: normal

ul
  list-style-type: none
  padding: 0

li
  display: inline-block
  margin: 0 10px

a
  color: #42b983

</style>
