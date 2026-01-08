
<template>
  <div class="about">
    <h1>This is an about page</h1>
    <button @click="change">点击</button>
  </div>
</template>
<script setup>
import { ref } from 'vue';


  let n=ref(10)
  function change(){
    n++
  }
  let m=ref(10)

</script>
<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
