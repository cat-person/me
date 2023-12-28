
<script setup>
import PersonalLink from './PersonalLink.vue';
</script>

<template>
  <div class="personal_panel">
    <h1>Aleksei Klyshnikov</h1>
    <!--Capitalise-->
    <h2>Senior Software Developer</h2>
    <div class="horizontal_layout">
      <PersonalLink logo_for="email" link="mailto:aleksei....@gmail.com" link_txt="aleksei....@gmail.com"/>
      <PersonalLink logo_for="ln" link="https://www.linkedin.com/in/alexey-klyshnikov" link_txt="Aleksei Klyshnikov"/>
    </div >
  </div>
</template>

<style>

.personal_panel {
  height: 5cm
}

.horizontal_layout {
  display: flex;
  flex-direction: row;
}

</style>