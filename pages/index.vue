<template>
  <div>
    <home-component />
    <about-component />
    <skill-page />
    <project-page />
    <contact-page />
  </div>
</template>

<script>
import HomeComponent from '@/components/home/HomeComponent'
import AboutComponent from '@/components/about/AboutComponent'
import SkillPage from '@/components/skill/SkillPage'
import ProjectPage from '@/components/project/ProjectPage'
import ContactPage from '@/components/contact/ContactPage'

export default {
  components: {
    HomeComponent,
    AboutComponent,
    SkillPage,
    ProjectPage,
    ContactPage
  }
}
</script>
