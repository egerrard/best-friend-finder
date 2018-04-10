<template>
  <div>
    <div class="row justify-content-sm-center">
      <div class="col-8 text-center">
        <h1>{{ msg }}</h1>
        <h5>
          Sick and tired of not having enough best friends?  Find yourself another best friend now!
        </h5>
      </div>
    </div>
    <div class="row justify-content-sm-center">
      <div class="col-8">
        <div class="form-group">
          <label>What type of best friend are you looking for?</label>
          <input class="form-control" v-model="species"/>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'BestFriendFinder',
  data() {
    return {
      msg: 'Best Friend Finder',
      species: '',
      breed: '',
      color: '',
      age: '',
      bff: []
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
