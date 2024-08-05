<script setup>
import DrawerHead from "@/components/DrawerHead.vue";
import CartItem from "@/components/CartItem.vue";
</script>

<template>
  <div class="fixed top-0 left-0 h-full w-full z-10 bg-black opacity-70"></div>

  <div class="fixed right-0 top-0 z-20 w-96 h-full bg-white p-8">
    <DrawerHead></DrawerHead>
    <CartItem></CartItem>
  </div>


</template>

