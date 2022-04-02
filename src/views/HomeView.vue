<script setup>
import Search from '@/components/Search.vue'
</script>

<template>
  <div id="title">
    <p>Galactic Codex</p>
  </div>
  <div id="search-container">
    <Search/>
  </div>
</template>

<style scoped>
  #search-container {
    float: none;
    max-width: 95%;
    width: 540px;
    margin: 7.4rem auto 1.95rem;
    text-align: center;
    vertical-align: middle;
  }

  #title {
    float: none;
    max-width: 95%;
    position: relative;
    margin: 7.4rem auto 1.95rem;
    width: 300px;
    font-size: 2rem;
    text-align: center;
  }

  div {
    display: block;
  }
</style>
