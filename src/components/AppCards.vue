<template lang="">
    <div class='cards-row'>
        <article v-for='card in cards' :key='card.series'>
          <img :src="card.thumb" alt="Card Image">
             <h2>{{card.series}}</h2>
        </article>
    </div>
</template>
<script>
export default {
  name: 'Cards',
  props: {
    cards: {
      type: Array,
      required: true,
    },
  },
};

</script>
<style lang="scss" scoped>
img {
    width: 100%;
    height: auto;
}

.cards-row{
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

article{
  width: calc((100% / 4 ) - 4rem);
}
</style>