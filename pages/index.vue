<template>
  <div>
    <home-component />
    <about-component />
    <contact-component />
  </div>
</template>

<script>
import HomeComponent from '@/components/home/HomeComponent'
import AboutComponent from '@/components/about/AboutComponent'
import ContactComponent from '@/components/contact/ContactComponent'

export default {
  components: {
    HomeComponent,
    AboutComponent,
    ContactComponent
  }
}
</script>
