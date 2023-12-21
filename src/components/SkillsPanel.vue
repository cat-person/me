<script>
import { ref } from 'vue'
export default {
  props: ['start_date', 'end_date', 'role', 'company', 'company_link', 'achievements'],
  setup(props) {
    const skills = ref([
      "Such agile",
      "Much progrumming",
      "Do smart stuff"
    ])

    return { skills }
  }
}
</script>

<template>
    <div class="skills">
      <h2>Skills</h2>
      <h3 v-for="skill in skills">
        {{skill}}
      </h3>
    </div>
</template>

<style scoped>
.skills{
  flex-direction: column;
  width: 100%;
  justify-content: left;
  background-color: blanchedalmond;
}  
</style>
