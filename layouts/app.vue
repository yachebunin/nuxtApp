<template>
  <div class="app">
    <Header
      class="header"
      @showPopup="showPopupHandler"
      @showSidebar="showSidebarHandler"
      :appSize="appSize"
    />
    <Sidebar
      @showSidebar="showSidebarHandler"
      v-if="appSize !== 1 || isShowSidebar"
      class="sidebar"
    />
    <div class="content">
      <Nuxt />
    </div>
    <Popup @showPopup="showPopup" v-if="isShow" />
  </div>
</template>

<script>
export default {
  data() {
    return {
      isShow: false,
      isShowSidebar: false,
      appSize: 3,
    };
  },
  mounted() {
    this.winWidth();
  },
  methods: {
    showSidebarHandler(show) {
      this.isShowSidebar = show;
    },
    winWidth: function () {
      setInterval(() => {
        let w = window.innerWidth;
        if (w < 768) {
          this.appSize = 1;
        } else if (w < 960) {
          this.appSize = 2;
        } else {
          this.appSize = 3;
        }
      }, 100); // для примера
    },
    showPopupHandler(show) {
      this.isShow = show;
    },
  },
};
</script>

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

<style scoped>
@media all and (max-width: 768px) {
  .app {
    grid-template-columns: auto;
    grid-template-rows: 40px auto;
    grid-template-areas:
      "header"
      "content";
  }
}
</style>