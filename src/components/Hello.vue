<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div class="badUsageOfVImg">
      <div v-img class="placeholder"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}

.placeholder {
  background-image: url('http://via.placeholder.com/100x100'); 
  width: 100px; 
  height: 100px; 
  margin: auto;
}
</style>
