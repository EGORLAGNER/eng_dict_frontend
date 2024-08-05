<script>
export default {
  data() {
    // хранение состояния (хранение данных)
    return {
      count: 0,
    }
  },
  methods: {
    // методы объекта
    increment() {
      this.count++
    },
    decrease() {
      this.count--
    },
    square() {
      this.count = this.count * this.count
    },
    reset() {
      this.count = 0
    }

  }
}
</script>


<template>
  <h3>Options API</h3>
  <h1>{{ count }}</h1>
  <p><button @click="increment">+</button></p>
  <p><button @click="decrease">-</button></p>
  <p><button @click="square">**</button></p>
  <p><button @click="reset">reset</button></p>
  <hr>
</template>

