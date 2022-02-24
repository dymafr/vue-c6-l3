<template>
  <button @click="toggle = !toggle">Toggle</button>
  <h1 v-show="toggle">Bonjout tout le monde !</h1>
  <h2 v-pre>{{ uneVariable }}</h2>
</template>

<script setup lang="ts">
import { ref } from 'vue';

const toggle = ref(true);
const uneVariable = ref('une valeur');
</script>

<style scoped lang="scss"></style>
