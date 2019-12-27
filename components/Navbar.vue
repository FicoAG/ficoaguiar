<template>
  <b-navbar cass="navbar">
    <template slot="end">
      <b-navbar-item href="#">Home</b-navbar-item>
      <b-navbar-item href="#">Documentation</b-navbar-item>
    </template>
  </b-navbar>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.navbar {
  position: -webkit-sticky; /* Safari */
  position: sticky;
  top: 0;
  background-color: #d84f00;
  color: white;
}
</style>