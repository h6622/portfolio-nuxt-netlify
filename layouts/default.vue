<template>
  <div>
    <header-component />
    <nuxt />
  </div>
</template>
<script>
import HeaderComponent from '@/components/HearderComponent'

export default {
  components: {
    HeaderComponent
  }
}
</script>
<style>
* {
  margin: 0;
  padding: 0;
}
.container {
  left: 0;
  right: 0;
  margin: 0 auto;
  width: 900px;
}
</style>
