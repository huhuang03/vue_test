<template>
  <div>{{isEdit? `Edit`: `Create`}} User</div>
<!--  <div>UserName: <input :value="{user.name}"/></div>-->
  <div>{{user.name}}</div>
</template>

<script setup lang="ts">
import type {User} from "@/User";
import {reactive, ref} from "vue";

const props = defineProps<{user?: User}>()
const user = reactive(props.user?? {})
</script>

<style scoped>

</style>
