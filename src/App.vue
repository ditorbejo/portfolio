<template>
  <!-- eslint-disable -->
  <HeaderComponent />
  <main>
    <HomeView />
  </main>
</template>

<script>
import HeaderComponent from "./components/HeaderComponent.vue";
import HomeView from "./views/HomeView.vue";

export default {
  components: {
    HeaderComponent,
    HomeView,
  },
};
</script>

<style>
:root {
  --cabinText: "Cabin Sketch", cursive;
  --poppinsText: "Poppins", sans-serif;
}
@import url("https://fonts.googleapis.com/css2?family=Cabin+Sketch:wght@400;700&family=Poppins:wght@400;500;600;700&display=swap");

#app {
  font-family: var(--poppinsText);
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
