<template>
  <div id="main-container">
    <carosel />
    <navbar />
    <h1>Medium</h1>
    <vfooter />
  </div>
</template>

<script>
import Carosel from '../components/carosel.vue'
import navbar from '../components/navbar.vue'
import vfooter from '../components/vfooter.vue'
export default {
  components: { navbar, Carosel, vfooter }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Prompt');

html,
body {
  font-family: 'Prompt', sans-serif;
}

#main-container {
  font-family: Prompt, Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
  max-width: 1440px;
  margin: auto;
}

#main-content {
  min-height: 900px;
  padding-top: 1%;
  padding-left: 2%;
  padding-right: 2%;
}
</style>
