<template>
  <div class="h1080 bgCharcoal d-flex align-center">
    <div class="container">
      <div class="d-flex">
        <img src="http://placehold.it/150X150" alt />
        <div style="margin-left:50px">
          <!-- <img src="http://placehold.it/150X150" alt /> -->
          1
          <br />1 <br />1
          <br />
          <br />
          <a class="btn">View More</a>
        </div>
      </div>
      <div class="skillDFlex">
        <div v-for="item in Imgs" :key="item">
          <img src="http://placehold.it/100x100" alt="img" />
        </div>
      </div>
      <div class="skillDFlex">
        <div v-for="item in Imgs" :key="item">
          <img src="http://placehold.it/100x100" alt="img" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      Imgs: [1, 2, 3, 4, 5]
    }
  }
}
</script>

<style scoped>
.title {
  font-family: 'Open Sans';
  font-size: 2rem;
  font-weight: bold;
}
.thisIntro {
  width: 100%;
}
.skillDFlex {
  height: 250px;
  display: flex;
  justify-content: space-around;
  align-items: center;
}
</style>
