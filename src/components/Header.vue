<script setup lang="ts">

</script>

<template>
  <header class="grid grid-cols-3 border-b-1 py-4">
    <div></div>
    <div class="text-lg">
      <h1>LINSHOES</h1>
    </div>
    <div class="text-right">
      <clarity:shopping-cart-solid />
      <ph:heart-fill class="mx-2" />
      <ph:user-fill />
    </div>
  </header>

  <nav class="flex justify-center py-3 text-gray-500">
    <div class="mx-5 flex items-center">
      <div class="">home</div><ic:baseline-keyboard-arrow-down />
    </div>
    <div class="mx-5">shop</div>
    <div class="mx-5">about</div>
  </nav>
</template>