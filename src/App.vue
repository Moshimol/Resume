<template>
  <left-nav class="left"></left-nav>
  <main-boad class="main"></main-boad>
</template>

<script>

import LeftNav from './components/LeftNav.vue';
import MainBoad from './components/MainBoard.vue';

export default {
  name: 'App',
  components: {
    LeftNav,
    MainBoad,
  },
  data() {
    return {

    };
  },
};
</script>

<style>
  /* * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    width: 100%;
    height: 100%;
  } */

  .left-nav {
    width: 300px;
    height:auto;
    float: left;
    margin-left: -100%;
    padding :48px 0;
    background-color: red;
  }

</style>
