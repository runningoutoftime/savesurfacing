<template>
  <div class="home">
    <div class="row">
      <IntroMessage></IntroMessage>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'
import IntroMessage from '@/components/IntroMessage.vue'
import ImageCard from '@/components/ImageCard.vue'

export default {
  name: 'home',
  components: {
    IntroMessage,
    ImageCard
  }
}


</script>

<style>
 .row {
   display: inline-flex;
   flex-wrap: wrap;
   justify-content: center;
 }
 .image-card {
   display: inline-block;
   border-radius: 30px;
   width: 350px;
   padding: 24px;
   background: white;
   margin: 8px;
 }
 .large-flex {
   flex: 1 0 100%;
   margin-top: 24px;
   margin-bottom: 24px;
 }
 .order-1 {
   order: -1;
 }
</style>
