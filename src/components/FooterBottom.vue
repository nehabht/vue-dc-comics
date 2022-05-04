<template>
    <div class="footer_bottom">
        <div class="container80">
          <div class="row flex_between">
            <div class="sign_up">SIGN-UP NOW!</div>
            <div class="social row">
              <div class="follow"> FOLLOW US</div>
              <div>
                <img src="../assets/img/footer-facebook.png" alt="">
                <img src="../assets/img/footer-twitter.png" alt="">
                <img src="../assets/img/footer-youtube.png" alt="">
                <img src="../assets/img/footer-pinterest.png" alt="">
                <img src="../assets/img/footer-periscope.png" alt="">
                
              </div>

            </div>
          </div>
        </div>
      </div>
</template>


<style lang="scss" scoped>
//footer bottom
.footer_bottom{
  background-color: #303030;
  color:white;
  height: 90px;
  display: flex;
  align-items: center;
}

.sign_up{
  padding: 8px;
  border: 1px solid #0282F9;
  font-size: 12px;
  font-weight:800;
}

.follow{
  margin-right: 20px;
  font-size: 12px;
  font-weight:800;
  color: #0282F9
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