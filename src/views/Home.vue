<template>
  <div class="home">
    <IntroMessage></IntroMessage>
    <ImageCard></ImageCard> <!-- FOR ALL image cards-->
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
