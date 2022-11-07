<template>
  <div>
    <button @click="increment">Increment</button>
  </div>
  <Child :count="count" />
</template>

<script setup lang="ts">

import Child from "@/Child.vue";
import {ref} from "vue";

const count = ref(1);
const increment = () => {
  count.value += 1
}
</script>

<style scoped>

</style>
