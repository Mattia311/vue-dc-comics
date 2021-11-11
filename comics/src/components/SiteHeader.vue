<template>
  <div id="siteHeader">
    <div class="container"> 
        <div class="img">
           <img src="../assets/dc-logo.png" alt=""> 
        </div>
        <div class="bar">
            <a href="#">CHARACTERS</a>
            <a href="#" class="active">COMICS</a>
            <a href="#">MOVIES</a>
            <a href="#">TV</a>
            <a href="#">GAMES</a>
            <a href="#">COLLECTIBLES</a>
            <a href="#">VIDEOS</a>
            <a href="#">FANS</a>
            <a href="#">NEWS</a>
            <a href="#">SHOP</a>
        </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
#siteHeader {
    width: 80%;
    margin: auto;
    .container {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding-top: 1rem;
    }
    img {
        width: 70px;
    }
    a {
        text-decoration: none;
        color: black;
        margin-left: 1.5rem;
        font-size: 13px;
        &.active {
            color:#0282F9;
            border-bottom: 6px solid #0282F9;
            padding-bottom: 2rem;
        }
    }
}


</style>