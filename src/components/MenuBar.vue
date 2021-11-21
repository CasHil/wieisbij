<template>
  <b-nav class="header">
    <a href="/">
      <img src="../assets/images/honeycomb.svg" alt="Logo" class="logo" />
    </a>
    <b-nav-item to="/">Home</b-nav-item>
    <b-nav-item to="/about">About</b-nav-item>
    <b-nav-item>Nieuw bijtje</b-nav-item>
  </b-nav>
</template>

<script>
export default {
  methods: {},
  props: {
    msg: String,
  },
};
</script>

<style lang="scss" scoped>
.header {
  background-color: $bee-yellow;
  position: sticky;
  top: 0;
  padding: 0.5rem 1rem;
  display: flex;
  flex-direction: row;
  margin: 0 auto;
}

.logo {
  width: 32px;
  height: 32px;
  margin: 0.5rem 1rem;
}
</style>
