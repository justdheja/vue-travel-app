<template>
  <div id="app">
    <div id="nav">
      <TheNavigation></TheNavigation>
    </div>
    <router-view :key="$route.path"/>
  </div>
</template>

<script>
import TheNavigation from './components/TheNavigation'
export default {
  components: {
    TheNavigation
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

</style>
