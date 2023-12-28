<script setup>
import SkillsPanel from './SkillsPanel.vue';

</script>

<template>
    <div class="side_panel">
      <div class="avatar_wrapper">
        <img class="avatar" src="@/assets/me.png"/>
      </div>
      <SkillsPanel/>
    </div>
</template>

<style scoped>

.side_panel{
  display: flex;
  flex-direction: column;
  height: 100%;
  width: 200px;
  padding: 20px;
  background-color: #263238;
}  

.avatar_wrapper {
  height: 5cm;
  width: 160px;
  display: flex;
  justify-content: center;
}
.avatar {
  height: 160px;
  width: 160px;
  border-radius: 50%;
}
</style>
