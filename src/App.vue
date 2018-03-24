<template>
  <div id="app">
    <img src="./assets/best-friends.jpg">
    <BestFriendFinder msg="Best Friend Finder"/>
  </div>
</template>

<script>
import BestFriendFinder from './components/BestFriendFinder.vue'

export default {
  name: 'app',
  components: {
    BestFriendFinder
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;

}
body {
  background-color:#fffce3;
}

</style>
