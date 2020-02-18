<template>
  <div class="homeContainer">
    <div class="container homeStyle">
      <h1 class="textCenter">Portfilo</h1>
      <h2 class="textCenter">This is my portfolio</h2>
      <h3 class="textCenter">button</h3>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.homeContainer {
  width: 100%;
  height: 500px;
  background: linear-gradient(
      rgba(100, 100, 100, 0.05),
      rgba(100, 100, 100, 0.5)
    ),
    url('~assets/images/bg.jpg');
  background-size: cover;
}

.homeStyle {
  padding: 180px 0;
}
</style>
