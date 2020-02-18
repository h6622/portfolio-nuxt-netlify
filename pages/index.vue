<template>
  <div>
    <home-component />
    <about-component />
    <skill-component />
    <contact-component />
  </div>
</template>

<script>
import HomeComponent from '@/components/home/HomeComponent'
import AboutComponent from '@/components/about/AboutComponent'
import SkillComponent from '@/components/skill/SkillComponent'
import ContactComponent from '@/components/contact/ContactComponent'

export default {
  components: {
    HomeComponent,
    AboutComponent,
    SkillComponent,
    ContactComponent
  }
}
</script>
