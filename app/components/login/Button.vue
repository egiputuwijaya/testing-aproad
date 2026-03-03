<script setup>
import { ref } from "vue";

const count = ref(0);

function increment() {
  count.value++;
}
</script>

<template>
  <button class="bg-blue-600 p-5" @click="increment">
    hallo indonesia {{ count }}
  </button>
</template>
