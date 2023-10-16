<script setup>
import {ref} from "vue";
import HelloWorld from "@/components/HelloWorld.vue";

let count = ref(0);
function handleClickAdd() {
  count.value++;
}
</script>

<template>
  <button v-on:click="handleClickAdd">+</button>
  <p>{{count}}</p>
  <HelloWorld msg=""></HelloWorld>
</template>

<style scoped>

</style>
