<template>
  <div class="page bg-gray-200">
    <Info class="main"/>
    <Showcase class="showcase"/>
    <Skillset class="skillset"/>
  </div>
</template>

<style>
  .page {
    min-height: 100vh;
    display: grid;
    grid-template-areas: "main" "sidebar" "showcase";
  }

  .main {
    grid-area: main;
  }

  .showcase {
    grid-area: showcase;
  }

  .skillset {
    grid-area: sidebar;
  }

  @media screen and (min-width: 1024px) {
    .main,
    .showcase {
      width: 100%;
      max-width: calc(724px - 2em);
    }

    .skillset {
      max-width: 300px;
    }

    .page {
      grid-template-areas: "main sidebar" "showcase sidebar";
      grid-template-columns: 1fr auto;
      grid-template-rows: auto 1fr;
    }
  }

  @media screen and (min-width: 1280px) {
    .main,
    .showcase {
      max-width: 900px;
    }
    .skillset {
      max-width: 440px;
    }
    .page {
      grid-template-columns: 2fr 1fr;
    }
  }
</style>
