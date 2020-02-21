<template>
  <div class="homeBg h1080 d-flex align-center">
    <div class="container">
      <div class="textCenter title lac MB1">Portfolio</div>
      <div class="textCenter lac">This Page is created by Vue.js</div>
      <div class="textCenter MY5">
        <a class="btn">View More</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.homeBg {
  background: linear-gradient(
      rgba(100, 100, 100, 0.05),
      rgba(100, 100, 100, 0.5)
    ),
    url('~assets/images/bg.jpg');
  background-size: cover;
}

.title {
  font-size: 3rem;
}
</style>
