<template>
  <div id="app">
    <TitleMy/>
  </div>
</template>

<script>
import TitleMy from './components/TitleMy.vue'

export default {
  name: 'App',
  components: {
    TitleMy
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
