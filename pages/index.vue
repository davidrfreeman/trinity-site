<template>
  <div>
    <b-jumbotron >
      <h1 class="jumbo_text display-3">Trinity Lutheran</h1>
      <h2 class="jumbo_text display-4">Church, Shchool, and Early Learning Center</h2>
    </b-jumbotron>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.jumbotron {
  /* background-image: url('~/assets/church.png'); */
  height: 93.5vh;
  background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),
    url("../assets/church.png");
  opacity: 0.8;
  background-size: cover;
}
.jumbo_text {
  color: #fff;
}
</style>
