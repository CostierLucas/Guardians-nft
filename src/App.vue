<template>
<Header></Header>
<Collections></Collections>
<Roadmap></Roadmap>
<Team></Team>
<Footer></Footer>
</template>

<script>
import Header from "./components/header.vue";
import Collections from "./components/collections.vue";
import Roadmap from "./components/roadmap.vue";
import Team from "./components/team.vue";
import Footer from "./components/footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Collections,
    Roadmap,
    Team,
    Footer,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap");

* {
  padding: 0;
  margin: 0;
  overflow-x: hidden;
}
#app {
  background-color: #000;
}
</style>
