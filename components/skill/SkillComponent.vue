<template>
  <div class="skillContainer bgCharcoal">
    <div class="container">
      <div class="skillDFlex">
        <div v-for="item in Imgs" :key="item">
          <img src="http://placehold.it/100x100" alt="img" />
        </div>
      </div>
      <div class="skillDFlex">test</div>
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
.skillContainer {
  width: 100%;
  height: 500px;
}

.skillDFlex {
  height: 250px;
  display: flex;
  justify-content: space-around;
  align-items: center;
}
</style>
