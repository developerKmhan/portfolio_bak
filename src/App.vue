<template>
  <div id="app">
    <Navbar />
    <Home /> 
    <Project />
  </div>
</template>

<script>
import Navbar from './components/navbar';
import Home from './components/home'; 
import Project from './components/projectList';

export default {
  name: 'App',
  components:{
    Navbar,
    Home,
    Project
  }
}
</script>

<style>

body{
  
  margin: 0;
}
</style>