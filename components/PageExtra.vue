<template>
  <div class="flex flex-col bg-gray-200">

    <SkillBox class="my-6" title="Core Skills" :skills="core"/>
    <SkillBox class="mb-6" title="Proficiencies" :skills="proficient"/>
    <SkillBox title="Other professional experience" :skills="decent"/>

    <div class="mt-auto py-6 px-12 text-center">
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
        proficient: [
          'NodeJS',
          'Webpack',
          'Typescript',
          'Linux sysadmin',
          'MongoDB',
          'SQL',
          'Readable code',
        ],
        decent: [
          'Agile',
          'REST',
          'Google APIs',
          'Facebook APIs',
        ],
      };
    },
  };
</script>
