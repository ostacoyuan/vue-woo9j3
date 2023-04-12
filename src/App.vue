<template>
  <div id="app">
    <h1>{{ msg }}</h1>
    <!-- DEMO 1 -->
    <img src="/profile.jpeg" alt="">
    <profile></profile>
    <education></education>
    <skills></skills>
  </div>
</template>

<script>

import Education from './Education.vue'
import Profile from './Profile.vue'
import Skills from './Skills.vue'
export default {
  components: {Education, Profile, Skills},
  name: 'app',
  data () {
    return {
      msg: 'Resume Application | Applicant: Ostaco, River Yuan'
    }
  }
}
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

h1, h2 {
  font-weight: normal;
}



a {
  color: #42b983;
}

p, h3, h2{
  font-size: 23px;
  text-align: left;
}

ul,li{
 text-align: left;
 font-size: 23px;
 padding-top: 5px;
}

img{
  padding: 0 15px 15px 15px;
  width: 20%;
  height: 20%;
  border-radius: 50%;
}
body{
  background-color: powderblue;
}
</style>
