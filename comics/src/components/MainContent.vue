<template>
  <div id="mainContent"> 
      <div class="topMain">
        <div>
            <h2>--> CONTENT GOES HERE </h2>
        </div>
      </div>
      <div class="bottomMain">
          <nav>
              <a href="#"><img class="imgMain" src="../assets/buy-comics-digital-comics.png" alt=""> DIGITAL COMICS</a>
              <a href="#"><img class="imgMain" src="../assets/buy-comics-merchandise.png" alt=""> DC MERCHANDISE</a>
              <a href="#"><img class="imgMain" src="../assets/buy-comics-subscriptions.png" alt=""> SUBSCRIPTION</a>
              <a href="#"><img class="imgMain" src="../assets/buy-comics-shop-locator.png" alt=""> COMICS SHOP LOCATOR</a>
              <a href="#"><img class="imgMain" src="../assets/buy-dc-power-visa.svg" alt=""> DC POWER VISA</a>
          </nav>
      </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
#mainContent {
    width: 100%;
    margin: auto;
    .topMain {
        background: black;
        h2 {
            color: white;
            padding: 3rem 0;
            width: 80%;
            margin: auto;
        }
        
    }
    .bottomMain {
        background: #0282F9;
        height: 150px;
        nav {
            width: 80%;
            margin: auto;
            display: flex;
            justify-content: space-around;
            align-items: center;
            padding-top: 47px;
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
}
</style>