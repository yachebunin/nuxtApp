<template>
  <div class="cards">
    <Card v-for="card in cards" :card="card" :key="card.id" />
  </div>
</template>

<script>
import Card from "./Card.vue";

export default {
  data() {
    return {
      cards: [
        {
          id: 0,
          payoutRate: 1,
          activePartners: 133,
          profiles: [
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
              isActive: true,
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
              isActive: true,
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
              isActive: false,
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
              isActive: false,
            },
          ],
        },
        {
          id: 1,
          payoutRate: 1,
          activePartners: 133,
          profiles: [
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
          ],
        },
        {
          id: 2,
          payoutRate: 1,
          activePartners: 133,
          profiles: [
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
          ],
        },
        {
          id: 3,
          payoutRate: 1,
          activePartners: 133,
          profiles: [
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
          ],
        },
        {
          id: 4,
          payoutRate: 1,
          activePartners: 133,
          profiles: [
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
          ],
        },
        {
          id: 5,
          payoutRate: 1,
          activePartners: 133,
          profiles: [
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
          ],
        },
        {
          id: 6,
          payoutRate: 1,
          activePartners: 133,
          profiles: [
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
          ],
        },
        {
          id: 7,
          payoutRate: 1,
          activePartners: 133,
          profiles: [
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
          ],
        },
        {
          id: 8,
          payoutRate: 1,
          activePartners: 133,
          profiles: [
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
          ],
        },
        {
          id: 9,
          payoutRate: 1,
          activePartners: 133,
          profiles: [
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
          ],
        },
        {
          id: 10,
          payoutRate: 1,
          activePartners: 133,
          profiles: [
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
          ],
        },
        {
          id: 11,
          payoutRate: 1,
          activePartners: 133,
          profiles: [
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
          ],
        },
        {
          id: 12,
          payoutRate: 1,
          activePartners: 133,
          profiles: [
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
          ],
        },
        {
          id: 13,
          payoutRate: 1,
          activePartners: 133,
          profiles: [
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
          ],
        },
      ],
    };
  },
  components: {
    Card,
  },
};
</script>

<style scoped>
.cards {
  display: flex;
  flex-wrap: wrap;
  max-width: 1300px;
  margin-left: 102px;
}
</style>