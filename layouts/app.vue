<template>
  <div class="app">
    <Header class="header" @showPopup="showPopup" />
    <Sidebar v-if="isMob" class="sidebar" />
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
      width: 0,
    };
  },
  created() {
    window.addEventListener("resize", this.updateWidth);
  },
  destroyed() {
    window.removeEventListener("resize", this.updateWidth);
  },
  methods: {
    isMob() {
      return this.width > 700;
    },
    showPopup(show) {
      this.isShow = show;
    },
    updateWidth() {
      this.width = window.innerWidth;
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