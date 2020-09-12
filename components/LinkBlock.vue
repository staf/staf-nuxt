<template>
  <block class="md:w-1/2 px-6 py-4 flex flex-row items-center">
    <h4 class="text-xl mr-auto">{{ title }}</h4>
    <slot/>
  </block>
</template>

<script>
  export default {
    props: ['title'],
  };
</script>
