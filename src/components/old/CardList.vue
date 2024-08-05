<script setup>
import Card from './Card.vue'
</script>

<template>
  <div class="grid grid-cols-4 gap-5">
    <Card image-url="/sneakers/sneakers-1.jpg"
          title="Мужские кроссовки"
          :price="9500"
          :is-added="true"
          :is-favorite="false"
          >

    </Card>
    <Card image-url="/sneakers/sneakers-2.jpg"></Card>
    <Card image-url="/sneakers/sneakers-3.jpg"></Card>
    <Card image-url="/sneakers/sneakers-4.jpg"></Card>
    <Card image-url="/sneakers/sneakers-5.jpg"></Card>
    <Card image-url="/sneakers/sneakers-6.jpg"></Card>

  </div>
</template>

