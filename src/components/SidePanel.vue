<script setup>
import SkillsPanel from './SkillsPanel.vue';
</script>

<template>
    <div class="side_panel">
      <div class="avatar_wrapper">
        <img class="avatar" src="@/assets/logo.svg"/>
      </div>
      <SkillsPanel class="skill_panel"/>
    </div>
</template>

<style scoped>

.side_panel{
  display: flex;
  flex-direction: column;
  height: 100%;
  width: 200px;
  justify-content: right;
  padding: 20px;
  background-color: bisque;
}  

.avatar_wrapper {
  height: 100px;
  width: 160px;
  display: flex;
  justify-content: center;
  background-color: blue;
}
.avatar {
  height: 100px;
  width: 100px;
  background-color: crimson;
}

.skill_panel {
  background-color: aqua;
}
</style>
