<template>
  <div id="app">
    <headerComponent />
    <main>
      content here
    </main>

    <buySectionComponent />

    <footer>
      <div class="footer_top">
        <div class="container80">
          <div class="row">
             <div class="col">
               <div class="col-4">
                 <h4>DC COMICS</h4>
                 <section>
                   <ul>
                      <li>lorem</li>
                      <li>lorem</li>
                      <li>lorem</li>
                      <li>lorem</li>
                      <li>lorem</li>
                      <li>lorem</li>
                   </ul>
                 </section>
                 <h4>SHOP</h4>
                 <section>
                   <ul>
                      <li>lorem</li>
                      <li>lorem</li>
                   </ul>

                 </section>
               </div>
               <div class="col-4">
                 <h4>DC</h4>
                 <section>
                   <ul>
                      <li>lorem</li>
                      <li>lorem</li>
                      <li>lorem</li>
                      <li>lorem</li>
                      <li>lorem</li>
                      <li>lorem</li>
                   </ul>
                 </section>
               </div>
               <div class="col-4">
                 <h4>SITES</h4>
                 <section>
                   <ul>
                      <li>lorem</li>
                      <li>lorem</li>
                      <li>lorem</li>
                      <li>lorem</li>
                      <li>lorem</li>
                      <li>lorem</li>
                   </ul>
                 </section>
               </div>

             </div>
            <div class="col">
              <img src="./assets/img/dc-logo-bg.png" alt="">
            </div>
          </div>
        </div>
       

      </div>

      <div class="footer_bottom"></div>
    </footer>

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

//footer top



.footer_top{
  width: inherit;
  height: 400px;
  background-image: url(./assets/img/footer-bg.jpg);

  color: white;
  display: flex;

    .col{
      display: flex;
      width: 50%;
      flex-grow: 1;

        img{
          height: 400px;

        }
         .col-4{
          padding-top: 1rem ;
          width: 25%;
        }
    }
}

h4{
  margin: 1rem 0;
}

ul{
  list-style: none;
}
li{
  font-size: 10px;
  color: lightgray
}



</style>
