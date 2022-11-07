<template>
  {{value}}
</template>

<script setup lang="ts">
import {ref, watch} from "vue";

const props = defineProps<{count: number}>()
const value = ref<number>(props.count)

watch(props, () => {
  value.value = props.count
})
</script>

<style scoped>

</style>
