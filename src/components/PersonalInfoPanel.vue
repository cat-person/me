
<script setup>
import PersonalLink from './PersonalLink.vue';
</script>

<template>
  <div class="personal_panel">
    <h1 class="me_title">Aleksei Klyshnikov</h1>
    <!--Capitalise-->
    <h2 class="me_subtitle">Senior Software Developer</h2>
    <div class="horizontal_layout">
      <PersonalLink logo_for="gh" link="https://github.com/cat-person" link_txt="cat-person"/>
      <PersonalLink logo_for="email" link="mailto:aleksei....@gmail.com" link_txt="aleksei....@gmail.com"/>
      <PersonalLink logo_for="ln" link="https://www.linkedin.com/in/alexey-klyshnikov-75b55763/" link_txt="Aleksei Klyshnikov"/>
    </div >
  </div>
</template>

<style>
  
  .me_title {
    height: 80px;
  }

  .me_subtitle {
    height: 48px;
  }

  .personal_panel {
    height: 200px;
    display: flex;
    width: fit-content;
    flex-direction: column;
    justify-content: center; 
  }

  .horizontal_layout {
    display: flex;
    width: fit-content;
    flex-direction: row;
    align-self: center;
  }

</style>