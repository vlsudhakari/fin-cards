<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <DeskCardsPage msg="Welcome to Your Desktop App" />
    <MobileCardPage msg="Welcome to Your Mobile App" />
  </div>
</template>

<script>
import DeskCardsPage from "./route-components/DeskCardsPage.vue";
import MobileCardPage from "./route-components/MobileCardPage.vue";

export default {
  name: "App",
  components: {
    DeskCardsPage,
    MobileCardPage,
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
