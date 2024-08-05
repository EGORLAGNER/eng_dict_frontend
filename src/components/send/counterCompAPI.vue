<script setup>
import {ref} from 'vue'

// задание реактивности для переменной
// под капотом это теперь объект
const count = ref(0)

function increment() {
  // задание нового значения переменной-объекту
  count.value++
}

function decrement() {
  count.value--
}

function square() {
  count.value = count.value * count.value
}

function reset() {
  count.value = 0
}


</script>

<template>
  {{ count }}
  <button @click="increment">+</button>
  <button @click="decrement">-</button>
  <button @click="square">**</button>
  <button @click="reset">reset</button>
  <hr>

</template>

<style scoped>

</style>