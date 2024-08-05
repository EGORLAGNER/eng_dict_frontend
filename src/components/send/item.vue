<script setup>
  defineProps({
    // специальная функция для пробрасывания данных
    title: String,
    price: Number,
    isAdded: Boolean,
  })
</script>

<template>
  <div class="product">
    <h2>Товар: {{ title }}</h2>
    <h2>Цена: {{ price }}</h2>
    <h2>Добавлен: {{ isAdded }}</h2>
    <slot></slot>
  </div>
</template>

<style scoped>
.product {
  border: 1px solid blue;
  padding: 10px;
  margin-bottom: 10px;
}
</style>


