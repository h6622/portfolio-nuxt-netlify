<template>
  <div class="thisContainer bgCharcoal">
    <div class="container">
      <div class="thisDFlex">
        <div v-for="item in items" :key="item">
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
      items: [1, 2, 3, 4, 5]
    }
  }
}
</script>

<style scoped>
.thisContainer {
  width: 100%;
  height: 500px;
}

.thisDFlex {
  height: 250px;
  display: flex;
  justify-content: space-around;
  align-items: center;
}
</style>
