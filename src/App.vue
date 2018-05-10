<template>
  <div id="app">
    <img src="./assets/logo.png">
    <transition name="fade">
      <router-view/>
    </transition>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="sass">
#app
  font-family: 'Avenir', Helvetica, Arial, sans-serif
  // -webkit-font-smoothing: antialiased
  // -moz-osx-font-smoothing: grayscale
  text-align: center
  color: #2c3e50
  margin-top: 60px

//  Анимации появления и исчезновения могут иметь
//  различные продолжительности и динамику.      
.fade-enter-active, .fade-leave-active 
  transition: opacity 0.25s ease-out

.fade-enter, .fade-leave-to
// .slide-fade-leave-active до версии 2.1.8 
  opacity: 0
  
</style>
