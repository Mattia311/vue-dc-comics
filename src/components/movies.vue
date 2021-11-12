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

<style>

</style>