<template>
  <signup_component/>
  <login_component/>
</template>

<script>
import signup_component from './components/signup_component.vue';
import login_component from './components/login_component.vue'
export default {
  name: 'App',
  components: {
    signup_component,
    login_component,
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
  margin-top: 60px;
}
</style>
