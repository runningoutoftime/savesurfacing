<template>
  <div class="intro">
    <span>S.A.V.E Surfacing</span>
    <p>We provide high quality Sport Court Surfacing at fair prices. Custom Designs are Available! </p>
    <a href="/contact">Contact Us Today</a>
  </div>
</template>

<script>
export default {
  name: 'IntroMessage',
  props: {
    msg: String,
    button: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
 .intro {
   display: inline-block;
   font-weight: bold;
   border-radius: 30px;
   width: 300px;
   padding: 48px;
   background: white;
   font-size: 22px;
 }
 a {
  color: white;
  padding: 16px;
  background: #42b983;
  border: none;
  border-radius: 8px;
  font-weight: bold;
  cursor: pointer;
  font-size: 18px;
 }
</style>
