<template>
  <div id="app">
    <headerComponent />
    <main>
      content here
    </main>

    <div class="buy_section">
      <div class="container70">
        <div class="cards_buy">
          <div class="card_buy">
            <img src="./assets/img/buy-comics-digital-comics.png" alt="">
            <p class="text_buy">digital comics</p>
          </div>
          <div class="card_buy">
            <img src="./assets/img/buy-comics-merchandise.png" alt="">
            <p class="text_buy">dc merchandise</p>
          </div>
          <div class="card_buy">
            <img src="./assets/img/buy-comics-subscriptions.png" alt="">
            <p class="text_buy">subscriptions</p>
          </div>
          <div class="card_buy">
            <img src="./assets/img/buy-comics-shop-locator.png" alt="">
            <p class="text_buy">comic shop locator</p>
          </div>
          <div class="card_buy">
            <img src="./assets/img/buy-dc-power-visa.svg" alt="">
            <p class="text_buy">dc power visa</p>
          </div>
        </div>


      </div>
    </div>

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

//buy section

.img{
  width: 100%;
}

.cards_buy{
  display: flex;
  height: 100px;


}

.card_buy{
  display: flex;
  flex-direction: row;
  align-items: center;
    flex-grow: 1;

  
    img{
      max-height: 35px;
    }

    p{
      color:white;
      padding-left: 1rem;
      text-transform: uppercase;
      font-size: 12px;
    }
  
}

</style>
