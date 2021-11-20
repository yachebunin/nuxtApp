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
              id: 0,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
              isActive: true,
            },
            {
              id: 1,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
              isActive: true,
            },
            {
              id: 2,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
              isActive: false,
            },
            {
              id: 3,
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
              id: 5,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 6,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 7,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 8,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 9,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 10,
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
              id: 11,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 12,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 13,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 14,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 15,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 16,
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
              id: 17,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 18,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 22,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 23,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 24,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 25,
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
              id: 26,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 27,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 28,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 31,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 32,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 33,
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
              id: 34,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 35,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 36,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 37,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 38,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 39,
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
              id: 41,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 42,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 43,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 44,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 45,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 46,
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
              id: 47,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 48,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 51,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 52,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 53,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 54,
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
              id: 56,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 57,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 58,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 59,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 61,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 62,
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
              id: 63,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 64,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 65,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 66,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 71,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 82,
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
              id: 89,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 91,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 112,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 113,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 114,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 115,
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
              id: 12312,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 2322,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 546,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 457,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 989,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 345,
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
              id: 9845,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 18234,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 2394,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 23495740923,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 9238475,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 3457239457324,
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
              id: 123123,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 234645,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 568568,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 870780,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 23452345,
              name: "kris_anfalova",
              img: require("../../assets/card/profile.png"),
            },
            {
              id: 7556,
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

<style scoped>
@media all and (max-width: 768px) {
  .cards {
    justify-content: space-between;
    margin-left: 0px;
  }
}
</style>