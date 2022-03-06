<script setup>
defineProps({
  header1 : {
      type : String,
      required: true,
  },
  header2 : {
    type : String,
    required: false,
    default : 'Не указано',
}
})
</script>

<template>
    <h1>{{header1}}</h1>
    <hr />
    <h3>{{header2}}</h3>
</template>

<style scoped>
</style>