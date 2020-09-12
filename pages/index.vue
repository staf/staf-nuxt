<template>
  <div class="page bg-gray-200">
    <Info class="main mx-auto"/>
    <Showcase class="showcase mx-auto"/>
    <Skillset class="skillset"/>
  </div>
</template>

<style>
  .page {
    min-height: 100vh;
    display: grid;
    grid-template-areas: "main sidebar" "showcase sidebar";
    grid-template-columns: 2fr 1fr;
    grid-template-rows: auto 1fr;
  }

  .main {
    grid-area: main;
  }

  .showcase {
    grid-area: showcase;
  }

  .main,
  .showcase {
    width: 100%;
    max-width: 900px;
  }

  .skillset {
    grid-area: sidebar;
    max-width: 440px;
  }
</style>
