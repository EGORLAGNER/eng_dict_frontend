<script setup>
import {ref} from "vue"

const count = ref(0)

function showMessage() {
  count.value = 'Hello Vue'
}

// function updateCount(event) {
//   count.value = Number(event.target.value)
// }


</script>

<template>
  {{ count }}
  <p><input @keyup.ctrl.enter="showMessage"></p>
</template>

<style scoped>

</style>