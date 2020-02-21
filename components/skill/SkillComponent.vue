<template>
  <div class="thisContainer bgCharcoal">
    <div class="container">
      <div class="thisDFlex">
        <div v-for="item in items" :key="item">
          <img src="http://placehold.it/100x100" alt="img" />
        </div>
      </div>

      <div class="thisDFlex">
        <div v-for="item in items" :key="item">
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
      items: [1, 2, 3, 4, 5]
    }
  }
}
</script>

<style scoped>
.thisContainer {
  width: 100%;
  height: 600px;
}

.thisDFlex {
  height: 300px;
  display: flex;
  justify-content: space-around;
  align-items: center;
}
</style>
