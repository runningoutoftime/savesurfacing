<template>
  <div class="home">
    <div class="row">
      <IntroMessage class="order-1" v-if="$mq != 'lg'"></IntroMessage>
      <img class="image-card" src="../assets/basketball-court1.jpeg"/>
      <img class="image-card" src="../assets/court1.jpeg"/>
      <img class="image-card" src="../assets/court2.jpeg"/>
      <IntroMessage class="large-flex" v-if="$mq === 'lg'"></IntroMessage>
      <img class="image-card" src="../assets/court3.jpeg"/>
      <img class="image-card" src="../assets/court4.jpeg"/>
      <img class="image-card" src="../assets/tennis-court1.jpeg"/>
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
   width: 300px;
   padding: 48px;
   background: white;
   margin: 8px;
 }
 .large-flex {
   flex: 1 0 100%;
 }
 .order-1 {
   order: -1;
 }
</style>
