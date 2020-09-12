<template>
  <div class="py-12 flex flex-col bg-gradient-to-r from-gray-100 to-gray-200">
    <SkillBox class="mb-6" title="Core Skills" :skills="core"/>
    <SkillBox class="mb-6" title="Tech Proficiencies" :skills="proficiencies"/>
    <SkillBox title="Useful Professional Experience" :skills="experience"/>
    <div class="mt-auto pt-12 text-center">
      <JobTitle/>
    </div>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        core: [
          'PHP',
          'Laravel',
          'JavaScript',
          'VueJS',
        ],
        proficiencies: [
          'NodeJS',
          'Webpack',
          'Typescript',
          'jQuery',
          'MongoDB',
          'SQL',
          'UX',
          'DX',
          'CSS',
          'Sass',
          'Bootstrap',
          'Highcharts',
        ],
        experience: [
          'Working remotely',
          'Agile',
          'Readable code',
          'Linux sysadmin',
          'nginx',
          'Apache',
          'Docker',
          'REST',
          'API Design',
          'Stripe',
          'Google APIs',
          'Facebook APIs',
        ],
      };
    },
  };
</script>
