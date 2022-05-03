<template>
    <div class="buy_section">
      <div class="container70">
        <div class="cards_buy">
          <div class="card_buy">
            <img src="../assets/img/buy-comics-digital-comics.png" alt="">
            <p class="text_buy">digital comics</p>
          </div>
          <div class="card_buy">
            <img src="../assets/img/buy-comics-merchandise.png" alt="">
            <p class="text_buy">dc merchandise</p>
          </div>
          <div class="card_buy">
            <img src="../assets/img/buy-comics-subscriptions.png" alt="">
            <p class="text_buy">subscriptions</p>
          </div>
          <div class="card_buy">
            <img src="../assets/img/buy-comics-shop-locator.png" alt="">
            <p class="text_buy">comic shop locator</p>
          </div>
          <div class="card_buy">
            <img src="../assets/img/buy-dc-power-visa.svg" alt="">
            <p class="text_buy">dc power visa</p>
          </div>
        </div>


      </div>
    </div>
</template>

<style lang="scss" scoped>

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