<template>
  <ul>
    <li v-for="gift in gifts">{{ gift }}</li>
  </ul>
</template>

<script>
export default {
  name: 'GiftsList',
  props: {
    gifts: Array,
  },
};
</script>

<style scoped>
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
</style>
