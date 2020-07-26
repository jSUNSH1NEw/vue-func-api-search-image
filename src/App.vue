<template>
  <div id="app">
    {{ mesage }}
  </div>
</template>

<script>
import { value } from 'vue-function-api';


export default {
  setup() {
    const message = value('Hello there ! 1337 CYBERPUNK-MAN');

    return {
      message,
    }
  }
};
</script>

<style>

</style>
