<template>
  <div id="app">
    <q10></q10>
    <q3></q3>
    <q4></q4>
    <q6></q6>
     <q7></q7>
     <q5></q5>
     <q8></q8>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import q10 from './components/q10.vue'
import q3 from './components/q3.vue'
import q4 from './components/q4.vue'
import q6 from './components/q6.vue'
import q7 from './components/q7.vue'
import q5 from './components/q5.vue'
import q8 from './components/q8.vue'

export default {
  name: 'App',
  components: {
    q10,q3,q4,q7,q5,q8,q6
  },
  //props:{
    //name:String
  //}
  
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
