<template>
  <HelloVue ></HelloVue>
  <CountOne></CountOne>
</template>

<script>
import CountOne from './components/CountOne.vue'
import HelloVue from './components/HelloVue.vue'

export default {
  name: 'App',
  components: {
    CountOne,
    HelloVue
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
