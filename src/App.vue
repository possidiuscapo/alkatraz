<template>
  <!-- html -->
 <!-- <HeaderCompo></HeaderCompo> -->
 <header-compo></header-compo>
 <main-compo></main-compo>
  <h1>welcome 👩‍🚀🚀</h1>
  
</template>

<style>
/* css */
h1{
  color: rgb(40, 40, 41);
}
</style>

<script>
// 
import  HeaderCompo from "./components/Header.vue";
import  MainCompo from "./components/Main.vue";
export default {
  components :{HeaderCompo, MainCompo}
}
</script>