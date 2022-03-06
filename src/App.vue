<script setup>
{/* Это строка комментария */}
{/* import HelloWorld from './components/HelloWorld.vue' */}
{/* import TheWelcome from './components/TheWelcome.vue' */}
import comp1 from './components/comp1.vue';
</script>

<template>
  <comp1 header1='Этот заголовок N1 задан параметром' />
  <comp1 header1='Этот заголовок N2 задан параметром' header2='Подзаголовок, задан вторым параметром'/>
</template>

<style>
@import './assets/base.css';

</style>
