<template>
  <div id="app">
    <h1>Hello, {{ name }} !</h1>
  </div>
</template>

<script lang="ts">
import Vue from 'vue';

export default Vue.extend({
  name: 'app',
  data: function() {
    return {
      name: 'Vue.js'
    }
  }
});
</script>

<style scoped>
</style>
