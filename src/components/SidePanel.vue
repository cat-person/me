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
  width: 220px;
  padding-left: 20px;
  background-color: #0E1B2B;
}  

.avatar_wrapper {
  height: 200px;
  display: flex;
  padding-top: 20px;
}
.avatar {
  height: 160px;
  width: 160px;
  border-radius: 50%;
}
</style>
