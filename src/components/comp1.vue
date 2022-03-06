<script setup>
defineProps({
  header1 : {
      type : String,
      required: true,
  }
})
</script>

<template>
    <h1>{{header1}}</h1>
    <hr />
    <h3>Подзаголовок</h3>
</template>

<style scoped>
</style>