<template>
  <div id="app">
    <!--<img alt="Vue logo" src="./assets/logo.png">-->
    <!--<HelloWorld msg="Welcome to Your Vue.js App"/>-->
    <!--<layout-train></layout-train>-->
    <!--<layout-train-page></layout-train-page>-->
    <container-train></container-train>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import LayoutTrain from './components/LayoutTrain'
// import LayoutTrainPage from './components/LayoutTrainPage'
import ContainerTrain from './components/ContainerTrain'


export default {
  name: 'app',
  components: {
    // HelloWorld,
    // LayoutTrain,
    // LayoutTrainPage,
    ContainerTrain
  }
}
</script>

<style>
  body {
    margin: 0;
  }
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0;
}
</style>

