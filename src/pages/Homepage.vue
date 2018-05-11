<template>
<main-layout>
  <div class="hello">
    <h1 class="singlepost">Posts</h1>
    <post heading="Whatever Title" subtitle="Lorem Ipsum Dolor Sit Amet" />
  </div>
</main-layout>

</template>

<script>
import MainLayout from '@/layout/MainLayout';
import Post from '@/components/Post';
export default {
  name: 'Homepage',
  data () {
    return {
      posts: [
        {id: 1, title: "BlaBlaBla 1"},
        {id: 2, title: "BlaBlaBla 2"},
        {id: 3, title: "BlaBlaBla 3"},
        {id: 4, title: "BlaBlaBla 4"},
        {id: 5, title: "BlaBlaBla 5"}
      ]
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
