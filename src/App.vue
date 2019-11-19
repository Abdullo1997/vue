<template>
  <div id="app">
    <headers></headers>
    <div class="container">
      <helloworld></helloworld>
      <footers></footers>
    </div>
  </div>
</template>
<script>
import HelloWorld from "./components/HelloWorld.vue";
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";
export default {
  components: {
    helloworld: HelloWorld,
    headers: Header,
    footers:Footer

  },
  data() {
    return {
      title: "Abdulloh Bobojonov"
    };
  },
  methods: {
    greeting: function() {
      return "Assalamu Alekum Hurmatli";
    }
  }
};
</script>

<style>
</style>
