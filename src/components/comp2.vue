<script setup>
import { reactive, computed, ref } from 'vue'

const comp2 = reactive({
  nameof: 'Товар',
  price: 125,
  count: 84,
});

defineProps(['title','price2'])

const overall = computed(() => {
  return comp2.price*comp2.count;
})
</script>

<template>
    <div class='computed'>
        <h3>{{title}} {{ overall2 }}</h3>
        <hr />
        <p>Наименование товара - {{comp2.nameof}}, количество - {{comp2.count}} шт.</p>
        <div class='result'> Цена за шт. - {{comp2.price}} руб., стоимость - {{ overall }} руб.</div>
        <p>Расчет стоимости выражением {{ comp2.price*comp2.count }}</p>
    </div>
</template>

<style scoped>
    .computed {
        background-color :aliceblue;
        color :black;
        margin-left: 50px;
        border : solid;
    }
    .computed .result {
        background-color : white;
        color:brown;
        border: solid;
        width : 50%;
    }
    
</style>