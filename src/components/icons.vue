<template>
  <div>
       <nav>
              <a href="#"><img class="imgMain" src="../assets/buy-comics-digital-comics.png" alt=""> DIGITAL COMICS</a>
              <a href="#"><img class="imgMain" src="../assets/buy-comics-merchandise.png" alt=""> DC MERCHANDISE</a>
              <a href="#"><img class="imgMain" src="../assets/buy-comics-subscriptions.png" alt=""> SUBSCRIPTION</a>
              <a href="#"><img class="imgMain" src="../assets/buy-comics-shop-locator.png" alt=""> COMICS SHOP LOCATOR</a>
              <a href="#"><img class="imgMain" src="../assets/buy-dc-power-visa.svg" alt=""> DC POWER VISA</a>
          </nav>
  </div>
</template>

<script>

export default {
    

}
</script>

<style lang="scss">
.bottomMain {
        background: #0282F9;
        height: 150px;
        nav {
            width: 80%;
            margin: auto;
            display: flex;
            justify-content: space-around;
            align-items: center;
            padding-top: 50px;
        }
        a {
            color: white;
            text-decoration: none;
            font-size: 13px;
        }
        .imgMain {
            width: 30px;
            vertical-align: middle;
        }
    }

</style>