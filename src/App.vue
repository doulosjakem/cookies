<template  id="top">
  <nav-bar />
  <blog />
  <custom-footer id="bottom" />
</template >

<script>
import NavBar from "./components/NavBar.vue";
import Blog from "./components/Blog.vue";
import CustomFooter from "./components/Footer.vue";
export default {
  name: "App",
  components: {
    NavBar,
    Blog,
    CustomFooter,
  },
};
</script>

<style>
.tan {
  background-color: #C3A57C;
}
.beige {
  background-color: #DB9A7D;
}
.brown {
  background-color: #634F40;
}
.ivory {
  background-color: #DED8CD;
}
</style>
