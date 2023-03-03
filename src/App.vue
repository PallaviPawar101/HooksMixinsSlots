<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to My Vue Training Tasks"/>
  <h1> Mixins</h1>
  <MixinA/>
  <h2>------------------------------------------</h2>
  <MixinB/>

  <h2>==========================================</h2>
  <h1>Slots in Vue</h1>
  <Child><h1>Learn Vue</h1></Child>
  <Child><img src="./assets/logo.png"></Child>
  <Child><a href="#">Leran Vue Here</a></Child>
  

</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MixinA from './components/MixinA.vue'
import MixinB from './components/MixinB.vue'
import Child from './components/Child.vue'
export default {
  name: 'App',
  components: {
    HelloWorld,
    MixinA,
    MixinB,
    Child
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
h1{
    color: orange;
 }
</style>
