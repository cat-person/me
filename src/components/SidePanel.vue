<script setup>
import SkillsPanel from './SkillsPanel.vue';

</script>

<template>
    <div class="side_panel">
      <div class="avatar_wrapper">
        <img class="avatar" src="@/assets/logo.svg"/>
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
  background-color:cornflowerblue;
}  

.avatar_wrapper {
  height: 100px;
  width: 160px;
  display: flex;
  justify-content: center;
}
.avatar {
  height: 100px;
  width: 100px;
}
</style>
