<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <div>
    <h1>{{ msg }}</h1>
    <p>Count: {{ count }}</p>
    <button @click="count++">Increment</button>
    <p class="read-the-docs">
      For more information, check out the
      <a href="https://vuejs.org/guide/introduction.html" target="_blank">Vue.js documentation</a>.
    </p>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
