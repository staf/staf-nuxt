<template>
  <div>
    <div class="pb-3 px-6 font-bold">
      {{ title }}
    </div>
    <div class="px-6 skill-list flex flex-row flex-wrap">
      <block
        v-for="skill in skills"
        :key="skill"
        class="py-1 px-2 text-sm mr-1 mb-1">
        <template>
          {{ skill }}
        </template>
      </block>
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
