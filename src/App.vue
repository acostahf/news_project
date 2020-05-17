<template>
  <div id="app">
    <Hero title="Hello World" msg="Welcome to Your Vue.js App" />
    <Contact title="Contact us" />
    <about title="About us" />
  </div>
</template>

<script>
import Hero from "./components/Hero.vue";
import Contact from "./components/Contact.vue";
import About from "./components/About.vue";

export default {
  name: "App",
  components: {
    Hero,
    Contact,
    About
  }
};
</script>
