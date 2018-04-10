<template>
  <div id="app" class="container">
    <div class="row  justify-content-center">
      <img src="./assets/best-friends.png">
    </div>
    <BestFriendFinder />
  </div>
</template>

<script>
import BestFriendFinder from './components/BestFriendFinder'

export default {
  name: 'app',
  components: {
    BestFriendFinder
  }
}
</script>

<style>
html, body {
  padding: 0.5rem;
  margin: 0;
  box-sizing: border-box;
  line-height: 1;
  background: linear-gradient(135deg, #31277D 0%,#D68B55 100%);
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
}
.container {
 
}

</style>
