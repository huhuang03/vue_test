<template>
  <h1>{{ isEdit? `Edit`: `Create`}} User</h1>
  <div>
    <span>Username: </span><input {{user?.name}}/>
  </div>
</template>

<script setup lang="ts">

</script>
