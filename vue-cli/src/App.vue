<template>
  <div id="app">
    <h1>CDShop</h1>
    <p class="animated fadeInRight">
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Assumenda soluta consequuntur tempore saepe placeat eos possimus quisquam et enim? Quis velit esse nihil, et culpa eaque at? Quisquam, saepe culpa.
    </p>
    <font-awesome-icon icon="shopping-cart"></font-awesome-icon>
    <price :value="4.23"></price>
  </div>
</template>

<script>
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome';
import Price from './components/Price.vue';

export default {
  name: 'App',
  components: {
    FontAwesomeIcon,
    Price,
  },
};
</script>
