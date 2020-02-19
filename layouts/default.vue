<template>
  <div>
    <header-component />
    <nuxt />
    <footer-component />
  </div>
</template>
<script>
import HeaderComponent from '@/components/HearderComponent'
import FooterComponent from '@/components/FooterComponent'

export default {
  components: {
    HeaderComponent,
    FooterComponent
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
.textCenter {
  text-align: center;
}
.textBold {
  font-weight: bold;
}
.textWhite {
  color: white;
}
.colorCharcoal {
  color: #343b41;
}
.bgCharcoal {
  background-color: #343b41;
}
.colorSky {
  color: #6cd6e3;
}
.bgSky {
  background-color: #6cd6e3;
}
</style>
