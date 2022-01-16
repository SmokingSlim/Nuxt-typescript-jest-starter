<template>
  <h2> Welcome to Tengai Next generation</h2>
</template>

<script lang="ts">

import Vue from 'vue';

export default Vue.extend({
  name: 'IndexPage',
  methods: {
    onClick():String {
      const lol: String = 'hellow worl';
      return lol;
    },
  },
});
</script>
