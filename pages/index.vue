<template>
  <div>
    <home-component />
    <about-component />
    <skill-component />
    <project-page />
    <contact-page />
  </div>
</template>

<script>
import HomeComponent from '@/components/home/HomeComponent'
import AboutComponent from '@/components/about/AboutComponent'
import SkillComponent from '@/components/skill/SkillComponent'
import ProjectPage from '@/components/project/ProjectPage'
import ContactPage from '@/components/contact/ContactPage'

export default {
  components: {
    HomeComponent,
    AboutComponent,
    SkillComponent,
    ProjectPage,
    ContactPage
  }
}
</script>
