<template>
  <div id="app" class="container mt-5">
    <h1>CDShop</h1>
    <p class="animate fadeInRight">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus
      molestias in animi qui odit blanditiis deleniti reprehenderit temporibus!
      Eligendi nostrum molestias nobis. Doloremque consequuntur, exercitationem
      nemo corrupti error amet repellendus!
    </p>
    <font-awesome-icon icon="shopping-cart"></font-awesome-icon>
  </div>
</template>

<script>
import { FontAwesomeIcon } from "@fortawesome/vue-fontawesome";

export default {
  name: "App",
  components: {
    FontAwesomeIcon,
  },
};
</script>
