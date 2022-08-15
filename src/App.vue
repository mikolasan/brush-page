<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <GettingStarted msg="Welcome to GutHub Brush!"/>
  <footer>
    <h3>Guthub Brush</h3>
    <ul>
      <li>This is a fun little Rust 🦀 learning project</li>
      <li>developed by <a href="https://twitter.com/mikolasan">@mikolasan</a></li>
    </ul>
  </footer>
</template>

<script>
import GettingStarted from './components/GettingStarted.vue'

export default {
  name: 'App',
  components: {
    GettingStarted
  }
}
</script>

<style>
body {
  margin: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 4rem;
}
img {
  max-height: 12rem;
}
footer {
  margin-top: 8rem;
  padding: 3rem;
  background-color: #2c3e50;
  color: #e3edf8;
}
a {
  color: #e3edf8;
}
ul {
  list-style-type: none;
}
</style>
