<template>

  
    <div>
          <img :src="image" alt="">
          <h3>{{titolo}}</h3>
    </div>
  

</template>

<script>
export default {
    props: {
        image: String,
        titolo: String

    }

}
</script>

<style lang="scss">
.container {
  display: flex;
  width: 80%;
  margin: auto;
  .img {
    max-width: 100%;
  }
}

</style>