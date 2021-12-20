<template>
  <div id="app">
    <Header />

    <main>
      Content goes here
    </main>

    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Footer
  },
};
</script>

<style lang="scss">
@import './style/general.scss';
@import './style/common.scss';
main {
  // TEST
  height: 100px;
  background-color: rgba(0, 0, 0, 0.849);
}
</style>
