<script setup>
import MySkillComponent from './components/Layout/MySkillComponent.vue'
import WhoAmIComponent from './components/Layout/WhoAmIComponent.vue'
import ExperienceAndEducationComponent from './components/Layout/ExperienceAndEducationComponent.vue'
import MyPortfolioComponent from './components/Layout/MyPortfolioComponent.vue'
import ReachOutComponent from './components/Layout/ReachOutComponent.vue'
import AboutMeComponent from './components/Layout/AboutMeComponent.vue'
</script>
<template>
    <div>
        <section class="px-8 py-6">
            <who-am-i-component></who-am-i-component>
        </section>
        <section class="px-8 py-6 mt-3 mb-3">
            <AboutMeComponent></AboutMeComponent>
        </section>
        <section class="px-8 py-6 mt-4 mb-4">
            <my-skill-component></my-skill-component>
        </section>
        <section class="px-8 py-6 mt-4 mb-4">
            <experience-and-education-component></experience-and-education-component>
        </section>
        <section class="px-8 py-6">
            <MyPortfolioComponent></MyPortfolioComponent>
        </section>
        <section class="px-8 py-6">
            <ReachOutComponent></ReachOutComponent>
        </section>
    </div>
</template>