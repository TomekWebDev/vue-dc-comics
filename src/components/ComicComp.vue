<template>
  <div class="comicCard">
    <img :src="dettagliProdotto.thumb" alt="" />
    <p>{{ dettagliProdotto.series.toUpperCase() }}</p>
  </div>
</template>

<script>
export default {
  name: "ComicComp",
  props: {
    dettagliProdotto: Object,
  },
};
</script>

<style lang="scss" scoped>
.comicCard {
  width: calc(90% / 6);
  color: white;
  margin: 0.3rem;

  img {
    width: 100%;
  }
}
</style>