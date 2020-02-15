<template>
  <div>
    <main-page />
    <about-page />
    <skill-page />
    <project-page />
    <contact-page />
  </div>
</template>

<script>
import MainPage from '@/components/main/MainPage'
import AboutPage from '@/components/about/AboutPage'
import SkillPage from '@/components/skill/SkillPage'
import ProjectPage from '@/components/project/ProjectPage'
import ContactPage from '@/components/contact/ContactPage'

export default {
  components: {
    MainPage,
    AboutPage,
    SkillPage,
    ProjectPage,
    ContactPage
  }
}
</script>
