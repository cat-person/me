<script setup>
import SkillsPanel from './SkillsPanel.vue';
</script>

<template>
    <div class="meow">
      <img class="avatar" src="@/assets/logo.svg"/>
      <SkillsPanel class="skill_panel"/>
    </div>
</template>

<style scoped>

.avatar {
  height: 100px;
  width: 100px;
  justify-self: center;
  background-color: blue;
}

.meow{
  display: flex;
  flex-direction: column;
  width: 40%;
  justify-content: right;
  background-color: bisque;
}  

.skill_panel {
  background-color: aqua;
  height: 80%;
  width: 100%;
}
</style>
