<template>
  <div id="app">
    <Body></Body>
  </div>
</template>

<script>
import Body from './components/Body.vue'
export default {
  name: 'app',
  data () {
    return {
      renderer : null
    }
  },
  mounted(){},
  components : {
    Body
  }
}
</script>

<style scoped>
#app {
  font-famly: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
