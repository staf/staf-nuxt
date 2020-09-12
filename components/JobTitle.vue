<template>
  <p class="italic text-gray-700">I am a <span class="">{{ title }}</span></p>
</template>

<script>
  export default {
    data() {
      return {
        titles: [
          'Full Stack Developer',
          'Software Engineer',
          'Developer',
          'Dad',
          'PHP Programmer',
          'Home Brewer',
          'Web Developer',
          'Gardener',
        ],
        index: 0,
      };
    },
    computed: {
      title() {
        return this.titles[this.index] || this.titles[0];
      },
    },
    mounted() {
      this.setTitle();
    },
    methods: {
      setTitle() {
        // Do I want to bother with selecting a random title?
        if (this.index < this.titles.length - 1) {
          this.index += 1;
        } else {
          this.index = 0;
        }

        setTimeout(() => this.setTitle(), 4000);
      },
    },
  };
</script>
