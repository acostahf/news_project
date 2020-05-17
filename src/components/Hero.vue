<template>
  <div class="hero is-primary is-fullheight">
    <div class="hero-body">
      <div class="container has-text-centered">
        <h1 class="title">{{ title }}</h1>

        <p class="is-size-5">{{ msg }}</p>
        <a href="#contactForm" class="button m-t-10">Contact us</a>
        <a href="#about-pg" class="button m-t-10">About us</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Hero",
  props: {
    title: String,
    msg: String
  }
};
</script>

<style>
.m-t-10 {
  margin-top: 30px;
}
</style>

<!-- Add "scoped" attribute to limit CSS to this component only -->
