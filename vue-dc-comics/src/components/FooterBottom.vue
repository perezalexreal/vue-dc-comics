<template>
    <div class="footer-bottom">
      <a href="#"><button class="button-sign-up">SIGN-UP-NOW</button></a> 
        <div class="container-logos">
            <h1>FOLLOW US</h1>
            <img src="../assets/footer-facebook.png" alt="">
            <img src="../assets/footer-periscope.png" alt="">
            <img src="../assets/footer-pinterest.png" alt="">
            <img src="../assets/footer-twitter.png" alt="">
            <img src="../assets/footer-youtube.png" alt="">
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
.footer-bottom {
    background-color: #1c1c1c;
    height: 110px;
    display: flex;
    justify-content: space-between;
    padding: 0 100px;
    align-items: center;

    a .button-sign-up {
        padding: 10px 40px;
        border: 2px solid royalblue;
        background-color: transparent;
        color: white;
        font-weight: bold;
        cursor: pointer;
    }
    .container-logos {
        display: flex;
        align-items: center;
        justify-content: space-around;

        h1 {
            color: royalblue;
            font-size: 17px;
            margin-right: 20px;
        }

        img {
            margin: 0px 6px;
            width: 30px;
            height: 30px;
        }
    }
}

</style>