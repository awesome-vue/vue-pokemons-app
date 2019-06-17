<template>
  <div id="app">
    Bonjour {{ name }} !
  </div>
</template>

<script lang="ts">
import Vue from 'vue';

export default Vue.extend({
  name: 'app',
  data () {
    return {
      name: 'Simon'
    }
  }
});
</script>

<style scoped>
</style>
