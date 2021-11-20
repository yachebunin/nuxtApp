<template>
  <div>
    <NuxtLink to="/structure" class="watch"> Посмотреть </NuxtLink>
  </div>
</template>

<script>
export default {
  layout: "default",
};
</script>

<style scoped>
.watch {
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
  color: #fff;
  font-size: 2em;
  text-decoration: none;
}
</style>