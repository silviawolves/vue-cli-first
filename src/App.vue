<template>
    <div>
      <titoloPagina></titoloPagina>
    </div>
</template>

<script>
import titoloPagina from './components/PageTitle.vue'

export default {
  components: {
    titoloPagina,
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
