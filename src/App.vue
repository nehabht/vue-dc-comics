<template>
  <div id="app">
    <header class="container80 navbar">
      <img class="logo_img" src="./assets/img/dc-logo.png" alt="">
      <nav>
        <ul>
          <li>Characters</li>
          <li class="active">Comics</li>
          <li>Movies</li>
          <li>Tv</li>
          <li>Games</li>
          <li>Collectibles</li>
          <li>Videos</li>
          <li>Fans</li>
          <li>News</li>
          <li>Shop</li>
        </ul>
      </nav>
    </header>

    <main>
      content here
    </main>
  </div>

</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {

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
  display: flex;
  justify-content: space-between;
  margin: 0 auto;
  padding: 1rem;

}

.navbar{
  height: 100px;
  align-items: center;
}

.logo_img{
  height: 60px;
  width: 60px;
}

ul{
  list-style: none;
    align-content: center;
}

li{
  display: inline;
  text-transform: uppercase;
  padding: 1rem;
  font-weight: 700;
  font-size: 11px;
}

.active{
  color: blue;

}

//main

main{
  width: 100%;
  background-color: black;
  height: 100px;
  color: white;
}

</style>
