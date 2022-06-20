<template>
    <div>
      <titoloPagina></titoloPagina>
      <jumbotron></jumbotron>
    </div>
</template>

<script>
import titoloPagina from './components/PageTitle.vue'
import jumbotron from './components/PageHero.vue'

export default {
  components: {
    titoloPagina,
    jumbotron,
  },
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
