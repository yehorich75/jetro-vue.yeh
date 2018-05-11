<template lang="pug">
main-layout
  .hello
    h1.singlepost SinglePostPage
    post
    post
    post
</template>

<script>
import MainLayout from '@/layout/MainLayout';
import Post from '@/components/Post';
export default {
  name: 'SinglePost',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components: {
    MainLayout,
    Post
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="sass">
h1.singlepost
  background: red

</style>
