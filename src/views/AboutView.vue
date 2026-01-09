
<template>
  <div class="about">
    <h1>This is an about page{{ n }}</h1>
    <button @click="change">点击</button>
    <myzujian ></myzujian>
  </div>
</template>
<script setup>
import { ref } from 'vue';
import myzujian from "../components/myzujian.vue"


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
