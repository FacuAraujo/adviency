<template>
  <div id="app">
    <h1>Regalos:</h1>
    <GiftsList v-bind:gifts="['PlayStation 5', 'Ipad', 'Componentes']" />
  </div>
</template>

<script>
import GiftsList from './components/GiftsList.vue';

export default {
  name: 'App',
  components: {
    GiftsList,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
