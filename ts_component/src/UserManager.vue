<template>
  <h1>Hello UserManager</h1>
  <UserEditOrCreate />
  <br />
  <br />

  <UserEditOrCreate :user="{name: 'Hello'}"/>
</template>

<script setup lang="ts">

import UserEditOrCreate from "@/UserEditOrCreate.vue";
</script>

<style scoped>

</style>
