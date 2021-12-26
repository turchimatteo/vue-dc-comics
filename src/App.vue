<template>
  <div id="app">
    <Header />
    <Jumbotron/>
    <ComicsList/>
    <Icons/>
    <Footer/>
    <FooterBottom/>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Jumbotron from "./components/Jumbotron.vue";
import ComicsList from "./components/ComicsList.vue";
import Icons from "./components/Icons.vue";
import Footer from "./components/Footer.vue";
import FooterBottom from "./components/FooterBottom.vue";

export default {
  name: "App",
  components: {
    Header,
    Jumbotron,
    ComicsList,
    Icons,
    Footer,
    FooterBottom
  },
};
</script>

<style lang="scss">
@import './style/general.scss';
@import './style/common.scss';
@import './style/variables.scss';
main {
  // TEST
  height: 100px;
  background-color: rgba(0, 0, 0, 0.849);
}
</style>
