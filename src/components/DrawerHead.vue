<script setup>
import { inject } from 'vue'

const { closeDrawer } = inject('cart')
</script>

<template>
    <div class="flex items-center gap-5 mb-5">
      <img @click="closeDrawer" src="/arrow-next.svg" alt="arrow" class="opacity-30 cursor-pointer rotate-180 hover:opacity-100 transition hover:translate-x-1" />
      <h2 class="text-2xl font-bold">Cart</h2>
    </div>
</template>