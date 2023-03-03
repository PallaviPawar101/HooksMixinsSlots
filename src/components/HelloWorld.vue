<template>
  <div class="hello">
    <h1> Check Console</h1>
      
    
    
    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data(){
   return {
    message : 'Hello Vue!' }
  },
   beforeCreate() {
     console.log("beforeCreate")
  },
  created(){
    console.log("created")
  },
  beforeMount(){
    console.log("beforeMount");
  },
  mounted(){
    setTimeout(function(){console.log("mounted()")}, 3000);
  },
  beforeUpdate() {
    console.log("beforeUpdate")
  },
  updated() {
    console.log("updated")
  },
  beforeUnmount() {
    console.log("beforeUnmount")
  },
  unmounted() {
    console.log("unmounted")
  }

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
