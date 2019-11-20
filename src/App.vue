<template>
  <div id="app">
    <div id="nav">
      <router-link to="/" class="margin-r">Home</router-link>
      <router-link to="/products" class="margin-r">Products</router-link>
      <router-link to="/contact">Contact</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
html {
  background: #ebf0f1;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 16px;
  background: white;
  margin-bottom: 24px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  font-size: 24px;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

.margin-r {
  margin-right: 24px;
}

</style>
