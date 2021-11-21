<template>
  <div>
    <div class="container">
      Lorem ipsum dolor sit, amet consectetur adipisicing elit. Magnam quia
      provident obcaecati labore iusto quo consectetur dicta hic, tenetur cum ex
      amet, sunt harum, eum omnis nostrum laboriosam error exercitationem?
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "Home",
  components: {},
});
</script>

<style lang="scss">
body {
  background-color: $bee-black;
  font-family: "Open Sans", sans-serif;
}

nav {
  background-color: $bee-yellow;
  position: -webkit-sticky;
  position: sticky;
  top: 0;
}
.container {
  margin: 0 auto;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: white;
  padding: 0.5rem 1rem;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
