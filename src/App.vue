<template>
  <div id="app">
    <headerComponent />
    

    <main>
      content here
    </main>
  </div>

</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import headerComponent from './components/Header.vue'
export default {
  name: 'App',
  components: {
    headerComponent,


  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

//main

main{
  width: 100%;
  background-color: black;
  height: 100px;
  color: white;
}

</style>
