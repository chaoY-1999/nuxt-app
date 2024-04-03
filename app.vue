<template>
  <div>
    <NuxtWelcome />
  </div>
</template>
<script setup>
const year: number = '2022'
const prop = toRefs<String>({ year })
</script>
