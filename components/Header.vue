<template>
  <div class="header">
    <div class="menu" v-if="appSize === 1"  @click="$emit('showSidebar', true)">
      burger
    </div>
    <span @click="$emit('showPopup', true)" class="title">Мероприятия</span>
  </div>
</template>

<script>
export default {
  props: ["appSize"],
};
</script>

<style scoped>
.header {
  display: flex;
  align-items: center;
  padding-left: 290px;
  color: #fff;
  background: #192233;
}

.title:hover {
  cursor: pointer;
}
</style>

<style scoped>
@media all and (max-width: 768px) {
  .header {
    padding-left: 0px;
    margin: 0px auto;
  }

  .menu {
    position: absolute;
    left: 40px;
  }
}
</style>