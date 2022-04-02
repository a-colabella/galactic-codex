<script setup>
  import IconSearch from '@/components/icons/IconSearch.vue'
</script>

<template>
  <div class="input_wrapper">
    <input type="text" placeholder="Search"/>
    <button class="search-button" type="submit"><IconSearch class="search-svg"/></button>
  </div>
</template>

<script>
  export default {
    name: 'Search',
    components: {
      IconSearch
    }
  }
</script>

<style scoped>
  .input_wrapper {
    display: inline-block;
    position: relative;
    vertical-align: top;
  }

  input {
    height: 1.5rem;
    border-width: 1px 0 1px 1px;
    border-radius: 2px 0 2px 2px;
    padding: 0.8rem 9.6rem .8rem 1.2rem;
    font-size: 1.2rem;
    line-height: 1.2rem;
  }

  .search-button {
    min-height: 1.6rem;
    margin: 0;
    border-radius: 0 2px 2px 0;
    padding: .8rem 1.6rem;
    font-size: 1.2rem;
    display: inline-block;
    cursor: pointer;
    position: relative;
    color: #fff;
    background-color: #333;
  }

  .search-svg {
    display: inline-block;
    vertical-align: middle;
    background-position: 0 -697px;
    height: 1.2rem;
  }
</style>
