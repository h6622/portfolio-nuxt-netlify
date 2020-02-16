<template>
  <div>
    <main-page />
    <about-component />
    <skill-page />
    <project-page />
    <contact-page />
  </div>
</template>

<script>
import MainPage from '@/components/main/MainPage'
import AboutComponent from '@/components/about/AboutComponent'
import SkillPage from '@/components/skill/SkillPage'
import ProjectPage from '@/components/project/ProjectPage'
import ContactPage from '@/components/contact/ContactPage'

export default {
  components: {
    MainPage,
    AboutComponent,
    SkillPage,
    ProjectPage,
    ContactPage
  }
}
</script>
