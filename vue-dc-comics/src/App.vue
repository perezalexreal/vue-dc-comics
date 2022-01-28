<template>
  <div id="app">
    <HeaderBox :nav="nav"/>
    <Jumbotron/>
    <MainContainer/>
    <Benefits/>
  </div>
</template>

<script>
import HeaderBox from "./components/HeaderBox.vue";
import Jumbotron from "./components/Jumbotron.vue";
import Benefits from "./components/Benefits.vue";
import MainContainer from "./components/MainContainer.vue";

export default {
  name: "App",
  components: {
    HeaderBox,
    Jumbotron,
    Benefits,
    MainContainer
  },
  data() {
    return {
      nav: [
        "Characters",
        "Comics",
        "Movies",
        "Tv",
        "Games",
        "Collectibles",
        "Videos",
        "Fans",
        "News",
        "Shop",
      ],
    };
  },
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Roboto&display=swap");

* {
  padding: 0px;
  margin: 0px;
  box-sizing: border-box;
  font-family: "Roboto", sans-serif;
}
</style>
