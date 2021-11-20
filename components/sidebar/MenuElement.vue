<template>
  <NuxtLink :to="`${element.path}`" class="element">
    <div class="icon"><img :src="element.icon" /></div>
    <div class="title">{{ element.title }}</div>
  </NuxtLink>
</template>

<script>
export default {
  name: "MenuElement",
  props: ["element"],
};
</script>

<style scoped>
.element {
  display: flex;
  align-items: center;
  padding-left: 25px;
  color: #fff;
  border-left: 4px solid transparent;
  text-decoration: none;
}

.element:not(:last-child) {
  margin-bottom: 28px;
}

.element:hover {
  cursor: pointer;
  color: #6781f7;
  border-left: 4px solid #6781f7;
}

.icon {
  margin-right: 20px;
}
</style>