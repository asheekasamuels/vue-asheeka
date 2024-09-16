<template>
  <div class="container">
    <section class="row" id= "landing">
      <LandingView/>

    </section>
    <section class="row" id= "about">
      <AboutView/>

    </section>
    <section class="row" id= "resume">
      <ResumeView/>

    </section>
    <section class="row" id= "projects">
      <ProjectsView/>

    </section>
    <section class="row" id= "contact">
      <ContactView/>

    </section>


  </div>
</template>

<script>
import LandingView from '@/components/LandingView.vue'
import AboutView from '@/components/AboutView.vue'
import ResumeView from '@/components/ResumeView.vue'
import ProjectsView from '@/components/ProjectsView.vue'
import ContactView from '@/components/ContactView.vue'
export default {
  name: 'HomeView',
  components: {
    LandingView,
    AboutView,
    ResumeView,
    ProjectsView,
    ContactView
  }
}
</script>

<style>

</style>