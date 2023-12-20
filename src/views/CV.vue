<script setup>
import ExperiencePanel from '@/components/ExperiencePanel.vue';
import PersonalInfoPanel from '@/components/PersonalInfoPanel.vue';
import SidePanel from '@/components/SidePanel.vue';
</script>

<template>

  <div class="cv">
    <SidePanel/>
    <div>
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
  padding: 20px;
}
</style>