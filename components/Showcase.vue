<template>
  <div class="flex flex-col md:mx-6 lg:mx-4 xl:mx-auto">
    <div class="md:flex flex-row mb-4 px-4 md:px-0">

      <LinkBlock title="My Work" class="mb-4 md:mr-2 md:mb-0">
        <a href="https://github.com/staf">
          <btn><span class="font-bold">@staf</span> on GitHub</btn>
        </a>
      </LinkBlock>

      <LinkBlock title="Find Me" class="md:ml-2">
        <a href="https://www.linkedin.com/in/linus-staf-80101079/">
          <btn>My LinkedIn profile</btn>
        </a>
      </LinkBlock>

    </div>

    <block class="mx-4 md:mx-0 text-center md:text-left">
      <div class="md:flex flex-row items-center p-6">
        <div>
          <h4 class="text-xl mb-3">Axtvetens Utveckling AB</h4>
          <p>I also have a company with which I have done some contracting with.</p>
        </div>

        <a href="https://axtveten.se" class="inline-block mt-3 md:mt-0 md:ml-auto">
          <btn>axtveten.se</btn>
        </a>
      </div>
    </block>

    <p class="mt-auto py-12 text-center text-gray-700">&copy; {{ new Date().getFullYear() }} Linus Staf</p>
  </div>
</template>
