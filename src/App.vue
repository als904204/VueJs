<script setup>
import { createApp, ref } from "vue";

const count = ref(0);

function counter () {
  count.value++;
}
</script>

<template>
  <button @click="counter">Count is : {{ count }}</button>
</template>

<style scoped>
  button {
    font-weight: bold;
  }
</style>
