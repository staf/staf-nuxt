<template>
  <button class="btn" @click="$emit('click', $event)"><slot/></button>
</template>

<style>
  .btn {
    @apply border border-gray-400 p-4 rounded-lg;
  }

  .btn:hover {
    @apply border-gray-800 shadow;
  }
</style>
