<template>
  <div class="app">
    <Header class="header" />
    <Sidebar class="sidebar" />
    <div class="content">
      <Nuxt />
    </div>
  </div>
</template>

<style>
body {
  margin: 0px;
  padding: 0px;
}
</style>

<style scoped>
.app {
  display: grid;
  grid-template-columns: 224px auto;
  grid-template-rows: 80px auto;
  grid-template-areas:
    "header header"
    "sidebar content";
  min-height: 100vh;
  background: #192233;
}

.header {
  grid-area: header;
}

.sidebar {
  grid-area: sidebar;
}

.content {
  grid-area: content;
}
</style>