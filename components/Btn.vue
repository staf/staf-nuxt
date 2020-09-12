<template>
  <button
    class="py-3 px-4 rounded-lg bg-teal-700 text-green-100 hover:bg-teal-600 hover:shadow"
    @click="$emit('click', $event)">
    <slot/>
  </button>
</template>
