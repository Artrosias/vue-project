<template>
  <h1>{{ title }}</h1>
</template>

<script> // JAVASCRIPT PATH

export default { // ROOT COMPONENT
  name: 'App',
  components: { },
  data() {
    return {
      title: 'Hello, World!'
    }
  }
}
</script>

<style> /* CSS PATH */
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1 {
  border-bottom: 1px solid #ddd;
  display: inline-block;
  padding-bottom: 10px;
}
</style>
