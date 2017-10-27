<template>
  <div class="home">
    <h1 > home component</h1>
    <router-link to="count"> goto count</router-link>
  </div>
</template>

<script>
export default {
  name: 'home',
  created(){
    console.log('home created');
  },
  activated(){
//    console.log('home activated');
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
</style>
