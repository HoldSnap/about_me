<script lang="ts">
import { defineComponent } from 'vue'
import BackgroundComponent from "@/components/backgroundComponent.vue";
import MeComponent from "@/components/meComponent.vue";
import AboutmeComponent from "@/components/aboutmeComponent.vue";
import HeadComponent from "@/components/headComponent.vue";
import StarComponent from "@/components/starComponent.vue";
import SkillsComponent from "@/components/skillsComponent.vue";
import ProjectsComponent from "@/components/projectsComponent.vue";
import TestComp from "@/components/testComp.vue";
import ConnectComponent from "@/components/connectComponent.vue";
import BasementComponent from "@/components/basementComponent.vue";

export default defineComponent({
  components: {
    BasementComponent,
    ConnectComponent,
    TestComp,
    ProjectsComponent,
    SkillsComponent,
    HeadComponent,
    StarComponent,
    AboutmeComponent,
    MeComponent,
    BackgroundComponent

  }
})
</script>

<template>
  <head-component></head-component>
  <star-component></star-component>
  <background-component />
  <me-component></me-component>
  <aboutme-component></aboutme-component>
  <skills-component></skills-component>
  <projects-component></projects-component>
  <connect-component></connect-component>
</template>

<style scoped></style>
