<template>
  <div id="app">
    <fft_renderer
            name="Wiegraf Folles"
            msg="If the penalty for a crime is a fine, then that law only exists for the lower class."/>
  </div>
</template>

<script>
import fft_renderer from './components/fft_renderer.vue'

export default {
  name: 'App',
  components: {
    fft_renderer
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
