<script setup>
import { ref } from "vue";
const name = ref("");
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <HelloWorld />
  <input v-model="name" type="text" />
  <div class="hi">Hi {{ name }}</div>
</template>

<!-- <style scoped>
.hi {
  border: solid 1px red;
}
</style> -->
