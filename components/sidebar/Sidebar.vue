<template>
  <div class="sidebar">
    <MenuElement
      v-for="element in menuElements"
      :element="element"
      :key="element.title"
    />
    <div v-if="isShowSidebar" class="close" @click="$emit('showSidebar', false)">
      close
    </div>
  </div>
</template>

<script>
import MenuElement from "./MenuElement.vue";

export default {
  data() {
    return {
      menuElements: [
        {
          title: "Дашборд",
          icon: require("../../assets/sidebar/home.svg"),
          path: "/",
        },
        {
          title: "Биржа активности",
          icon: require("../../assets/sidebar/discuss.svg"),
          path: "/",
        },
        {
          title: "Биржа блогеров",
          icon: require("../../assets/sidebar/group.svg"),
          path: "/",
        },
        {
          title: "Взаимопиар",
          icon: require("../../assets/sidebar/pr.svg"),
          path: "/pr",
        },
        {
          title: "Моя структура",
          icon: require("../../assets/sidebar/structure.svg"),
          path: "/structure",
        },
        {
          title: "Магазин",
          icon: require("../../assets/sidebar/store.svg"),
          path: "/",
        },
        {
          title: "Марафон",
          icon: require("../../assets/sidebar/marathon.svg"),
          path: "/",
        },
        {
          title: "Лендинги",
          icon: require("../../assets/sidebar/landings.svg"),
          path: "/",
        },
      ],
    };
  },
  props: ['isShowSidebar'],
  components: {
    MenuElement,
  },
};
</script>

<style scoped>
.sidebar {
  padding-left: 10px;
  color: #fff;
  background: #192233;
}
</style>

<style scoped>
@media all and (max-width: 768px) {
  .sidebar {
    position: fixed;
    left: 0px;
    min-height: 100%;
    min-width: 210px;
    padding: 50px 20px 20px;
    background: #192233;
    z-index: 100;
  }

  .close {
    position: absolute;
    left: 260px;
    top: 50px;
  }

  .close:hover {
    cursor: pointer;
  }
}
</style>