<template>
  <div class="header" @click="$emit('showPopup', true)">
    <span class="title">Мероприятия</span>
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