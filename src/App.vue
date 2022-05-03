<template>
  <div id="app">
    <headerComponent />
    <main>
      content here
    </main>

    <buySectionComponent />

    <footer>
      <bottomTopComponent />
      <div class="footer_bottom"></div>
    </footer>

  </div>

</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import headerComponent from './components/Header.vue'
import buySectionComponent from './components/BuySection.vue'
import bottomTopComponent from './components/BottomTop.vue'
export default {
  name: 'App',
  components: {
    headerComponent,
    buySectionComponent,
    bottomTopComponent,


  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

  color: #2c3e50;
}
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}


.container80{
  width: 80%;
  margin: 0 auto;
}

.container70{
  width: 70%;
  background-color: transparent;
  height: 100px;
  margin: 0 auto;
}

.row{
  display: flex;
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
