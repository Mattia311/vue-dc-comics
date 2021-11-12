<template>
  <div id="siteFooter">
      <div class="topFooter">
          <div class="container">
           <div class="row">
            <div class="col-6">
                <div class="col-4">
                  <h2>DC COMICS</h2>
                  <ul>
                      <li>Characters</li>
                      <li>Comics</li>
                      <li>Movies</li>
                      <li>TV</li>
                      <li>Games</li>
                      <li>Videos</li>
                      <li>News</li>
                  </ul>
                  <h2>SHOP</h2>
                  <ul>
                      <li>Shop DC</li>
                      <li>Shop DC Collectibles</li>
                  </ul>
                </div>
                <div class="col-4">
                  <h2>DC</h2>
                  <ul>
                      <li>Terms Of Use</li>
                      <li>Privacy Policy (New)</li>
                      <li>Ad Choices</li>
                      <li>Advertising</li>
                      <li>Jobs</li>
                      <li>Subscriptions</li>
                      <li>Talent Workshops</li>
                      <li>CPSC Cerificates</li>
                      <li>Ratings</li>
                      <li>Shop Help</li>
                      <li>Contact Us</li>
                  </ul>
                </div>
                <div class="col-4">
                  <h2>SITES</h2>
                  <ul>
                      <li>DC</li>
                      <li>MAD Magazine</li>
                      <li>DC Kids</li>
                      <li>DC Universe</li>
                      <li>DC Power Visa</li>
                  </ul>
                </div>
            </div>
            <div class="col-6">
                <div class="imgFooter">
                    <img src="../assets/dc-logo-bg.png" alt="">
                </div>
            </div>
           </div>

          </div>
      </div>
      <div class="bottomFooter">
          <div class="container">
            <button>SIGN-UP NOW!</button>
            <div class="follow">
                <h2>FOLLOW US</h2>
                <i> <img src="../assets/footer-facebook.png" alt=""></i>
                <i> <img src="../assets/footer-twitter.png" alt=""></i>
                <i> <img src="../assets/footer-youtube.png" alt=""></i>
                <i> <img src="../assets/footer-pinterest.png" alt=""></i>
                <i> <img src="../assets/footer-periscope.png" alt=""></i>
            </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
.topFooter {
    background-image: url('../assets/footer-bg.jpg');
    height: 400px;
    background-repeat: no-repeat;
    background-size: cover;
    h2 {
        color: white;
        padding-top: 2.5rem;
        padding-bottom: 1rem;
        font-size: 17px;
    }
    .row {
        width: 80%;
        margin: auto;
        display: flex;
        li {
            color: #5F5F5F;
            list-style: none;
            line-height: 20px;
            font-size: 12px;
        }
        .col-6 {
            display: flex;
            .col-4 {
                margin-right: 40px;
            }
            .imgFooter {
                margin-left: 200px;
                img {
                    width: 400px;

                }
            }
        }
    }
}
.bottomFooter {
    background: #303030;
    height: 115px;
    .container {
        padding-top: 34px;
        width: 80%;
        margin: auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
        button {
            background: #303030;
            color: white;
            border: 1px solid #0282F9;
            height: 50px;
            width: 130px;
        }
        .follow {
            display: flex;
            align-items: center;
            h2 {
                color: #0B7CF1;
                margin-right: 20px;
            }
            i {
                margin: 0px 10px;
            }

        }
    }
}

</style>