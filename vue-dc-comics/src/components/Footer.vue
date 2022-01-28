<template>
    <div class="footer">
        <div class="main-footer">
            <div class="footer-nav">
                <h1>DC Comics</h1>
                <p>Characters</p>
                <p>Movies</p>
                <p>Tv</p>
                <p>Games</p>
                <p>Videos</p>
                <p>News</p>
            </div>
            <div class="footer-nav">
                <h1>dc</h1>
                <p>Terms Of User</p>
                <p>Privacy Policy (New) </p>
                <p>Ad Choices</p>
                <p>Avertising</p>
                <p>Jobs</p>
                <p>Subscriptions</p>
                <p>Talent Worshops</p>
                <p>CPSC Certificates</p>
                <p>Ratings</p>
                <p>Shop Help</p>
                <p>Contact Us</p>
            </div>
            <div class="footer-nav">
                <h1>Sites</h1>
                <p>DC</p>
                <p>MAD Magazine</p>
                <p>DC Kids</p>
                <p>DC Universe</p>
                <p>DC Power Visa</p>
            </div>
            <div class="footer-nav">
                <h1>shop</h1>
                <p>Shop DC</p>
                <p>Shop DC Collectibles</p>
            </div>
         
        </div>
           <img class="logo-footer" src="../assets/dc-logo-bg.png" alt="">
    </div>
</template>


<script>
export default {
    
}
</script>

<style lang="scss" scoped>
.footer {
    width: 100%;
    padding: 0 100px;
    background: url('../assets/footer-bg.jpg') no-repeat;
    background-size: cover;
    background-position: right;
    height: 400px;
    overflow: hidden;
    color:white;
    display: flex;
    flex-direction: row;
    justify-content: space-between;

    .main-footer {
        padding: 40px 0px;
        display: flex;
        justify-content: left;
max-width: 550px;

        .footer-nav {
            margin: 0px 20px;
            

            h1 {
                text-transform: uppercase;
                font-size: 18px;
                margin-bottom: 20px;
            }

            p {
                font-size: 14px;
                margin: 5px 0px;
                color: gray;
            }
        }
    }
    
}

.logo-footer {
    position: relative;
    width: 500px;
    height: 500px;
    overflow: hidden;
    bottom: 50px;
}
</style>