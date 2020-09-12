<template>
  <div class="page">
    <PageMain class="page-main"/>
    <PageExtra class="page-extra"/>
    <PageSidebar class="page-sidebar"/>
  </div>
</template>

<style>
  .page {
    min-height: 100vh;
    display: grid;
    grid-template-areas: "main extra sidebar";
    grid-template-columns: 2fr 1fr auto;
  }

  .page-main {
    grid-area: main;
  }

  .page-extra {
    grid-area: extra;
  }

  .page-sidebar {
    grid-area: sidebar;
  }
</style>
