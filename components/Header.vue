<template>
  <div class="header">
    <span @click="$emit('showPopup', true)" class="title">Мероприятия</span>
  </div>
</template>

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