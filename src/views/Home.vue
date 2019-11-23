<template>
  <div class="home">
    <div class="row">
      <IntroMessage class="order-1" v-if="$mq != 'lg'"></IntroMessage>
      <img class="image-card" src="../assets/court1.jpg"/>
      <img class="image-card" src="../assets/court2.jpg"/>
      <img class="image-card" src="../assets/court3.jpg"/>
      <IntroMessage class="large-flex" v-if="$mq === 'lg'"></IntroMessage>
      <img class="image-card" src="../assets/court4.jpg"/>
      <img class="image-card" src="../assets/court5.jpg"/>
      <img class="image-card" src="../assets/court6.jpg"/>
      <img class="image-card" src="../assets/court7.jpeg"/>
      <img class="image-card" src="../assets/court8.jpg"/>
      <img class="image-card" src="../assets/court9.jpg"/>
      <!-- <IntroMessage class="large-flex" v-if="$mq === 'lg'"></IntroMessage> -->
      <img class="image-card" src="../assets/court10.jpg"/>
      <img class="image-card" src="../assets/court11.jpg"/>
      <img class="image-card" src="../assets/court12.jpg"/>
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
