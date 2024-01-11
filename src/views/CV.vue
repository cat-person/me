<script setup>
import ExperiencePanel from '@/components/ExperiencePanel.vue';
import EducationPanel from '@/components/EducationPanel.vue';
import PersonalInfoPanel from '@/components/PersonalInfoPanel.vue';
import SidePanel from '@/components/SidePanel.vue';
import '@/global.css';
 
</script>

<template>
  <div class="cv">
    <SidePanel/>
    <!-- <img class="bg" src="@/assets/background.svg"> -->
    <div class="data">
      <PersonalInfoPanel/>
      <ExperiencePanel  class="experience_bg"/>
      <EducationPanel  class="experience_bg"/>
    </div>
  </div>  
</template>

<style>
.cv {
  height: 100%;
  width: 100%;
  display: flex;
  flex-direction: row;
  justify-content: bottom;
  align-items: end;
}

.experience_bg {
  background-color: aqua;
}

.bg {
  width: 1024px;
  height: fit-content;
  position: absolute;
}

.data {
  height: 100%;
  width: 100%;
  padding: 20px;
}
</style>