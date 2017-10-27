<template>
  <div>
   <h1>count component</h1>
    <router-link to="/">goto home</router-link>
  </div>

</template>
<script>
  export default {
//    name:'count',
    created(){
      console.log('count created');
    },
    activated(){
      console.log('count activated');
    }
  }
</script>
<style>

</style>
