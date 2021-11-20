<template>
  <div class="profile">
    <img
      class="img"
      :src="profile.img"
      :class="{ activeProfile: profile.isActive }"
    />
    <span>{{ profile.name }}</span>
  </div>
</template>

<script>
export default {
  props: ["profile"],
};
</script>

<style scoped>
.profile {
  display: flex;
  align-items: center;
  font-size: 8px;
}

.profile:not(:last-child) {
  margin-bottom: 10px;
}

.profile > span {
  opacity: 0.5;
}

.img {
  width: 25px;
  margin-right: 5px;
  opacity: 0.5;
}

.activeProfile {
  opacity: 1;
}
</style>