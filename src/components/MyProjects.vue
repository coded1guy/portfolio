<script setup lang="ts">
import ProjectCard from "../components/ProjectCard.vue";
</script>
<template>
  <section id="projects">
    <h2>My Projects</h2>
    <div class="project-content">
      <ProjectCard
        project-title="APIConf website"
        project-link="https://apiconf.net/"
        project-desc="I implemented several components of the APIConf website which was interfaced by over 100+ attendees."
        project-lang="Vite, Reactjs, TS, TailwindCSS"
      />
      <ProjectCard
        project-title="RadioAdSpread"
        project-link="https://radioadspread.com/"
        project-github=""
        project-desc="I contributed to the development of the frontend implementation of the RadioAdspread web-app."
        project-lang="React, Next, JS"
      />
      <ProjectCard
        project-title="NewFrontiers"
        project-link="https://www.newfrontierslearning.com/"
        project-github=""
        project-desc="I worked with a team-mate at Dumela Corp to build this website for our client, NewFrontiers."
        project-lang="Wix website builder"
      />
      <ProjectCard
        project-title="NewFrontiers LMS"
        project-link="https://lms.newfrontierslearning.com/"
        project-github=""
        project-desc="I maintain and serve as a technical support engineer for this LMS. The LMS was developed by Dumela Corp for one of their client, NewFrontiers."
        project-lang="moodle, BigBlueButton, PHP"
      />
      <ProjectCard
        project-title="ED-Tech landing page"
        project-link="https://emmo-ed-tech.netlify.app/"
        project-github="https://github.com/coded1guy/ed-tech"
        project-desc="I implemented the figma design of an ed-tech landing page with reactjs."
        project-lang="Reactjs, CSS, JS"
      />
      <ProjectCard
        project-title="Portfolio"
        project-link="https://emmanuel-olubiyi.vercel.app/"
        project-github=""
        project-desc="I designed and developed this portfolio website for myself."
        project-lang="Vuejs, CSS, TS"
      />
    </div>
  </section>
</template>

<style>
.project-content {
  margin-top: 20px;
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  gap: 30px;
  align-items: center;
}
@media screen and (min-width: 650px) {
  .project-content {
    display: flex;
    flex-flow: row wrap;
    justify-content: space-between;
    align-items: center;
  }
}
</style>
