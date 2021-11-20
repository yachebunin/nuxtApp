<template>
  <div class="card">
    <div class="info">
      <div class="payoutRate">
        <div>{{ card.payoutRate }}</div>
        <div>Уровень выплат</div>
      </div>
      <div class="activePartners">
        <div>{{ card.activePartners }}</div>
        <div>Активных партнёров</div>
      </div>
    </div>

    <div class="profiles">
      <Profile
        v-for="profile in card.profiles"
        :key="profile.name"
        :profile="profile"
      />
    </div>
  </div>
</template>

<script>
import Profile from "./Profile.vue";

export default {
  props: ["card"],
  components: {
    Profile,
  },
};
</script>

<style scoped>
.card {
  max-width: 119px;
  max-height: 228px;
  margin: 0px 35px 35px 0px;
  padding: 15px;
  background: #192233;
  border-radius: 20px;
}

.info {
  display: flex;
  margin-bottom: 23px;
  font-size: 8px;
}

.payoutRate {
  margin-right: 15px;
}

.payoutRate > div:first-child,
.activePartners > div:first-child {
  padding-bottom: 2px;
  font-size: 12px;
  border-bottom: 1px solid #707d96;
}

.payoutRate > div:last-child,
.activePartners > div:last-child {
  padding-top: 2px;
}

.profiles {
  max-height: 130px;
  overflow: auto;
}

.profiles::-webkit-scrollbar {
  width: 1px;
  background-color: #111824;
}

.profiles::-webkit-scrollbar-thumb {
  background-color: #707d96;
}
</style>