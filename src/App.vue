<template>
  <div id="app">
    <p>{{message}}</p>
  </div>
</template>

<script>
import { Value } from 'vue-function-api';

export default {
  setup() {
    const message = Value('Hello there ! 1337 CYBERPUNK-MAN');

    return {
      message,
    };
  },
};
</script>

<style>

</style>
