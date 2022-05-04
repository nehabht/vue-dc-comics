<template>
  <div id="app">
    <headerComponent />
    <main>
      content here
    </main>

    <buySectionComponent />

    <footer>
      <footerTopComponent />
      <footerBottomComponent />
    </footer>

  </div>

</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import headerComponent from './components/Header.vue'
import buySectionComponent from './components/BuySection.vue'
import footerTopComponent from './components/FooterTop.vue'
import footerBottomComponent from './components/FooterBottom.vue'
export default {
  name: 'App',
  components: {
    headerComponent,
    buySectionComponent,
    footerTopComponent,
    footerBottomComponent,


  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  display: flex;
  flex-direction: column;
  min-height: 100vh
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

.flex_between{
  justify-content: space-between;
}

//main

main{
  width: 100%;
  background-color: black;
  min-height: 100px;
  color: white;
  flex: 1
}

</style>
