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
    <h1 class='title'>{{header1}}</h1>
    <hr />
    <h3 class='subtitle'>{{header2}}</h3>
</template>

<style scoped>
    .title {
        font-size: 28px;
        color: blueviolet;
        }
    .subtitle{
        font-size: 20px;
        color: darkblue;
        background-color: beige;
        }
</style>