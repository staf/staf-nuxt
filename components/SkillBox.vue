<template>
  <div>
    <div class="pb-3 px-12 font-bold">
      {{ title }}
    </div>
    <div class="px-12 skill-list flex flex-row flex-wrap">
      <div v-for="skill in skills" class="rounded-lg bg-white border-b border-gray-400 py-1 px-2 text-sm mr-1 mb-1">
        {{ skill }}
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    props: ['title', 'skills'],
  };
</script>

<style>
  .skill-list {
    grid-template-columns: repeat(auto-fill, 80px);
  }
</style>
