
<script setup>
import PersonalLink from './PersonalLink.vue';
</script>

<template>
  <div>
    <h1>Aleksei Klyshnikov</h1>
    <!--Capitalise-->
    <h2>SENIOR SOFTWARE DEVELOPER</h2>
    <div class="horizontal_layout">
      <PersonalLink logo_for="email" link="mailto:aleksei....@gmail.com" link_txt="aleksei....@gmail.com"/>
      <PersonalLink logo_for="gh" link="https://github.com/cat-person" link_txt="cat-person"/>
    </div >
    <div  class="horizontal_layout">
      <PersonalLink logo_for="ln" link="https://www.linkedin.com/in/alexey-klyshnikov" link_txt="Aleksei Klyshnikov"/>
      <PersonalLink logo_for="phone" link="tel: *******" link_txt="*****"/>
    </div>
  </div>
</template>

<style>

.horizontal_layout {
  display: flex;
  flex-direction: row;
}

</style>