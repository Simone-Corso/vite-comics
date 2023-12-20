<template lang="">
    <div>
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
   

</style>