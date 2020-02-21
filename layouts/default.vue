<template>
  <div>
    <header-component />
    <nuxt />
    <footer-component />
  </div>
</template>

<script>
import HeaderComponent from '@/components/HeaderComponent'
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

.d-flex {
  display: flex;
}

.align-center {
  align-items: center;
}

.justify-center {
  justify-content: center;
}

.justify-space-between {
  justify-content: space-between;
}

.h1080 {
  height: 1080px;
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

.lac {
  font-family: 'Lacquer';
}

.MB1 {
  margin-bottom: 1rem;
}

.MX1 {
  margin-left: 1rem;
  margin-right: 1rem;
}

.MY1 {
  margin-bottom: 1rem;
  margin-top: 1rem;
}

.MX5 {
  margin-left: 5rem;
  margin-right: 5rem;
}

.MY5 {
  margin-bottom: 5rem;
  margin-top: 5rem;
}

.PY3 {
  padding-bottom: 3rem;
  padding-top: 3rem;
}

.PY5 {
  padding-bottom: 5rem;
  padding-top: 5rem;
}

.btn {
  font-size: 20px;
  background-color: #424954;
  color: #6cd6e3;
  padding: 0.5rem 1rem;
  border-radius: 5px;
}
</style>
