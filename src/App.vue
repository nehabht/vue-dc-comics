<template>
  <div id="app">
    <headerComponent />
    <main>
      content here
    </main>

    <buySectionComponent />

  </div>

</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import headerComponent from './components/Header.vue'
import buySectionComponent from './components/BuySection.vue'
export default {
  name: 'App',
  components: {
    headerComponent,
    buySectionComponent,


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

.container80{
  width: 80%;
}

.container70{
  width: 70%;
  background-color: transparent;
  height: 100px;
  margin: 0 auto;
}

.buy_section{
  background-color: #2c3e50;
}
//main

main{
  width: 100%;
  background-color: black;
  height: 100px;
  color: white;
}



</style>
