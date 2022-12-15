<template>
  <div class="container-fluid brown text-center">
    <intro />
    <dry-ingredients id="dry" />
    <wet-ingredients id="wet" />
    <drop id="drop" />
    <recipe id="recipe" />
  </div>
</template>

<script>
import Intro from "./instructions/Intro.vue";
import DryIngredients from "./instructions/DryIngredients.vue";
import WetIngredients from "./instructions/WetIngredients.vue";
import Drop from "./instructions/Drop.vue";
import Recipe from "./instructions/Recipe.vue";
export default {
  components: {
    Intro,
    DryIngredients,
    WetIngredients,
    Drop,
    Recipe,
  },
};
</script>

<style>
.backdrop {
  text-shadow: 0px 0px 10px white;
}
img {
  box-shadow: 5px 5px 10px;
}
div.container {
  border: 10px solid black;
  border-top: none;
}
</style>