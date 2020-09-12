<template>
  <div class="flex flex-col">
    <div class="flex flex-row mb-4">

      <block class="w-1/2 mr-2 px-6 py-4 flex flex-row items-center">
        <h4 class="text-xl mr-auto">My work</h4>
        <a href="https://github.com/staf">
          <btn><span class="font-bold">@staf</span> on GitHub</btn>
        </a>
      </block>

      <block class="w-1/2 ml-2 px-6 py-4 flex flex-row items-center">
        <h4 class="text-xl mr-auto">Find me</h4>
        <a href="https://www.linkedin.com/in/linus-staf-80101079/">
          <btn>My LinkedIn profile</btn>
        </a>
      </block>

    </div>

    <block>
      <div class="flex flex-row items-center p-6">
        <div>
          <h4 class="text-xl mb-3">Axtvetens Utveckling AB</h4>
          <p>I also have a company with which I have done some contracting with.</p>
        </div>

        <a href="https://axtveten.se" class="ml-auto">
          <btn>axtveten.se</btn>
        </a>
      </div>
    </block>

    <p class="mt-auto py-12 text-center text-gray-700">&copy; {{ new Date().getFullYear() }} Linus Staf</p>
  </div>
</template>
