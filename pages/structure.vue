<template>
  <div class="structure">
    <div class="title">Моя структура</div>
    <Cards />
  </div>
</template>

<script>
import Cards from "../components/structure/Cards.vue";

export default {
  layout: "app",
  components: {
    Cards,
  },
};
</script>

<style scoped>
.structure {
  min-height: calc(100% - 53px);
  padding: 52px 0px 0px 64px;
  color: #fff;
  background: #212c42;
  border-radius: 50px 50px 0px 0px;
}

.title {
  margin: 0px 0px 147px 16px;
  font-weight: 700;
  font-size: 40px;
}
</style>