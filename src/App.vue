<template>
   
  <Weatherapp></Weatherapp>
</template>

<script>
import Weatherapp from './components/WeatherApp.vue'
export default {
  name: 'App',
 components:{
   Weatherapp,
  
 }, 
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
 
  color: #2c3e50;

}


</style>
