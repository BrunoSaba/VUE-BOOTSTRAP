<template>
  <div id="app">
    <app-sectionCard/>
    <app-tables/>  
  </div>
</template>

<script>
import SectionCard from './sectioncard'
import Tables from './tables'

export default {
  name: 'App',
  components: {
    'app-sectionCard': SectionCard, 'app-tables': Tables
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
  margin-top: 10px;
  margin-left: 20px;
  margin-right: 20px;
}

</style>
