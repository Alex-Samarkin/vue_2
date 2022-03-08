<script setup>
import comp1 from './components/comp1.vue';
import comp2 from './components/comp2.vue';
</script>

<template>
  <comp1 header1='Этот заголовок N1 задан параметром' />
  <comp1 header1='Этот заголовок N2 задан параметром' header2='Подзаголовок, задан вторым параметром'/>
  
  <comp2 title='Расчет цены 1' price2='10' />
  <comp2 title='Расчет цены 2' price2='20' />
</template>

<style>
@import './assets/base.css';

</style>
