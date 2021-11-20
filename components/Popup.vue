<template>
  <div class="popup">
    <div class="title">Мой попап, зачем тыкнул?</div>
    <input type="text">
    <input type="text">
    <div class="ok" @click="$emit('showPopup', false)">Понял, зря быканул</div>
  </div>
</template>

<style scoped>
.popup {
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
  background: #000;
  color: #fff;
  border-radius: 20px;
  padding: 20px;
}

.title {
  margin-bottom: 10px;
}

.ok {
  margin-top: 10px;
}

.ok:hover {
  cursor: pointer;
}
</style>