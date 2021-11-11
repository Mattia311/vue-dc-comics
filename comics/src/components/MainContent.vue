<template>
  <div id="mainContent"> 
      <div class="topMain">
        <div>
            <h2>--> CONTENT GOES HERE </h2>
        </div>
      </div>
      <div class="bottomMain">
         <icons/>
      </div>
    </div>
</template>

<script>
import icons from '../components/icons.vue';
export default {
    components: {
    icons
  }

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
    /*.bottomMain {
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
    }*/
}
</style>