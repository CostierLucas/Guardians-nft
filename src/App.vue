<template>
  <Loading :isLoading="isLoading" />
  <main v-if="!isLoading">
    <Header></Header>
    <Collections></Collections>
    <Roadmap></Roadmap>
    <Team></Team>
    <Faq></Faq>
    <Footer></Footer>
  </main>
</template>

<script>
import Header from "./components/header.vue";
import Collections from "./components/collections.vue";
import Roadmap from "./components/roadmap.vue";
import Team from "./components/team.vue";
import Faq from "./components/faq.vue";
import Footer from "./components/footer.vue";
import Loading from "./components/loading.vue";

export default {
  name: "App",
  components: {
    Header,
    Collections,
    Roadmap,
    Team,
    Faq,
    Footer,
    Loading,
  },
  data() {
    return { isLoading: true };
  },
  mounted() {
    setTimeout(() => {
      this.isLoading = false;
    }, 3000);
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Orbitron:wght@400;500;700&display=swap");

* {
  padding: 0;
  margin: 0;
  overflow-x: hidden;
}

#app {
  background-color: #000;
}
</style>
