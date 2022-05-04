<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <h1>{{ msg }}</h1>
  <ImageCompo :list_items="items"> </ImageCompo>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import ImageCompo from './components/image.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
    ImageCompo
  },
  data(){
    return{
      msg: 'Items List',
      items: [
        'Hey, do not rush to make decisions!',
        'There is time for everything! So, hurry up!',
        'I know you know it! I know you know not it!',
        'React vs Vue OR React vs Vue but not Angular',
        'Spring vs Node OR Spring vs Node',
        'Deung deung deung... deung deung deung...'
      ]
    }

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
