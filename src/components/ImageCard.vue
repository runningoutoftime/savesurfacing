<template>
  <div class="image-card">
    <img src="../assets/logo.png">
  </div>
</template>

<script>
export default {
  name: 'ImageCard',
  props: {
    imageSrc: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
 .image-card {
   display: inline-block;
   border-radius: 30px;
   width: 300px;
   padding: 48px;
   background: white;
   margin: 8px;
 }
</style>
