<style>
html,
body {
  padding: 0;
  margin: 0;
}
.container {
  display: flex;
  flex-direction: column;
  flex: 1;
  justify-content: space-between;
}
</style>

<script>
import Header from "./components/layout/Header.vue";
import Footer from "./components/layout/Footer.vue";
import Contents from "./components/layout/Contents.vue";
export default {
  name: "Container",
  components: {
    Header,
    Contents,
    Footer,
  },
};
</script>

<template>
  <div class="container">
    <Header></Header>
    <Contents></Contents>
    <Footer></Footer>
  </div>
</template>
