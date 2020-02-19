<template>
  <div class="thisContainer bgSky">
    <div class="container thisWidth">
      <p style="text-align:center; margin-bottom: 40px">Contact</p>
      <div class="thisDFlex">
        <input id type="text" value="name" name />
        <input id type="text" value="e-mail" name />
      </div>
      <textarea id name cols="30" rows="10" class="thisTextArea"></textarea>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.thisContainer {
  width: 100%;
  height: 400px;
}

.thisWidth {
  width: 400px;
}

.thisTextArea {
  width: 100%;
}

.thisDFlex {
  display: flex;
  justify-content: space-between;
}
</style>
