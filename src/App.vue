<template>
  <div id="app">
    <img style="width:200px" src="http://athletics.stolaf.edu/custompages/logos/athletics/stolaf-on-white.jpg">
      <my-vuetable></my-vuetable>
    </div>
  </div>
</template>

<script>
import MyVuetable from './components/MyVuetable';

export default {
  name: 'app',
  components: {
    MyVuetable
  }
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>