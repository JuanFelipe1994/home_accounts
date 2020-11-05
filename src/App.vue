<template>
  <div id="app">
    <h1 class="d-block py-3 bg-info text-white">
      <div class="container">
        Gestion del hogar <span class="material-icons">apartment</span>
      </div>
    </h1>
    <div class="container">
      <service-calculator></service-calculator>
    </div>
  </div>
</template>

<script>
import serviceCalculator from './components/serviceCalculator';

export default {
  name: 'App',
  components: {
    serviceCalculator,
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
  h1 {
    font-size: 22px;
    span {
      font-size: 2rem;
    }
  }
}
</style>
