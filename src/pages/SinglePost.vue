<template>
<main-layout>
  <div class="hello">
    <h1 class="singlepost">SinglePostPage</h1>
  </div>
</main-layout>
</template>

<script>
import MainLayout from '@/layout/MainLayout';
export default {
  name: 'SinglePost',
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
h1.singlepost
  background: red

</style>
