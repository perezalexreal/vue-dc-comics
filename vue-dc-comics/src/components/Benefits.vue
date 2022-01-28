<template>
    <div class="benefits">
        <div class="container-benefits">
            <img src="../assets/buy-comics-digital-comics.png" alt="">
            <p> Digital Comics</p>
        </div>
        <div class="container-benefits">
            <img src="../assets/buy-comics-merchandise.png" alt="">
            <p> DC Merchandise</p>
        </div>
        <div class="container-benefits">
            <img src="../assets/buy-comics-subscriptions.png" alt="">
            <p> Subscription</p>
        </div>
        <div class="container-benefits">
            <img src="../assets/buy-comics-shop-locator.png" alt="">
            <p> Comic Shop Locator</p>
        </div>
        <div class="container-benefits">
            <img src="../assets/buy-dc-power-visa.svg" alt="">
            <p> Dc Power Visa</p>
        </div>
    </div>
</template>


<script>
export default {
    
}
</script>

<style lang="scss" scoped>
  .benefits {
      background-color: royalblue; 
      background-size: cover;
      height: 130px;
      display: flex;
      justify-content: space-around;
      padding: 0px 100px;
      align-items: center; 
      color: white;

      .container-benefits{
          display: flex;
          flex-direction: row;
          align-items: center;
          justify-content: space-around;

          img {
              height: 40px;
              margin-right: 20px;
          }
      }
  }

</style>