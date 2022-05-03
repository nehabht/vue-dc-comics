<template>
  <div id="app">
    <headerComponent />
    <main>
      content here
    </main>

    <buySectionComponent />

    <footer>
      <bottomTopComponent />
      <div class="footer_bottom">
        <div class="container80">
          <div class="row flex_between">
            <div class="sign_up">SIGN-UP NOW!</div>
            <div class="social row">
              <div class="follow"> FOLLOW US</div>
              <div>
                <img src="./assets/img/footer-facebook.png" alt="">
                <img src="./assets/img/footer-twitter.png" alt="">
                <img src="./assets/img/footer-youtube.png" alt="">
                <img src="./assets/img/footer-pinterest.png" alt="">
                <img src="./assets/img/footer-periscope.png" alt="">
                
              </div>

            </div>
          </div>
        </div>
      </div>
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

.buy_section{
  background-color: #2c3e50;
}
//main

main{
  width: 100%;
  background-color: black;
  min-height: 100px;
  color: white;
  flex: 1
}

//footer bottom
.footer_bottom{
  background-color: #2c3e50;
  color:white;
  height: 90px;
  display: flex;
  align-items: center;
}

.sign_up{
  padding: 8px;
  border: 1px solid blue;
  font-size: 12px;
  font-weight:800;
}

.follow{
  margin-right: 20px;
  font-size: 12px;
  font-weight:800;
}

.social{
    display: flex;
    align-items: center;

  img{
    width: 25px;
    margin: 0 5px
  }
}


</style>
