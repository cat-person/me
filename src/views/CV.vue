<script setup>
import ExperiencePanel from '@/components/ExperiencePanel.vue';
import PersonalInfoPanel from '@/components/PersonalInfoPanel.vue';
import SidePanel from '@/components/SidePanel.vue';
</script>

<template>
  <div class="cv">
    <SidePanel/>
    <!-- <img class="bg" src="@/assets/background.svg"> -->
    <div class="data">
      <PersonalInfoPanel/>
      <ExperiencePanel/>
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

.bg {
  width: 1024px;
  height: fit-content;
  position: absolute;
}

.data {
  height: 100%;
  width: 100%;
  display: flex;
  flex-direction: column;
}
</style>