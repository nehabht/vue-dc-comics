<template>
    <div class="footer_top">
        <div class="container80">
          <div class="row flex_between">
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
            <div class="col flex_end">
              <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>
          </div>
        </div>
    </div>
    
</template>

<style lang="scss" scoped>
//footer top

.flex_end{
  justify-content: flex-end;
}


.footer_top{
  width: inherit;
  height: 300px;
  background-image: url(../assets/img/footer-bg.jpg);
  

  color: white;
  display: flex;

    .col{
      display: flex;
      width: 50%;
      flex-grow: 1;

        img{
          height: 300px;
          

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