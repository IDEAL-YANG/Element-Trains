<template>
  <div id="app">
    <!--<img alt="Vue logo" src="./assets/logo.png">-->
    <!--<HelloWorld msg="Welcome to Your Vue.js App"/>-->
    <!--<layout-train></layout-train>-->
    <layout-train-page></layout-train-page>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import LayoutTrain from './components/LayoutTrain'
import LayoutTrainPage from './components/LayoutTrainPage'

export default {
  name: 'app',
  components: {
    // HelloWorld,
    LayoutTrain,
    LayoutTrainPage
  }
}
</script>

<style>
  body {
    margin: 0px;
  }
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}
</style>

