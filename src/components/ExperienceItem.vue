<script>
import { ref } from 'vue'
export default {
  props: ['start_date', 'end_date', 'role', 'company', 'company_link', 'achievements'],
  setup(props) {
    const full_link = `https://${props.company_link}`
    return { full_link }
  }
}
</script>

<template>
  <div class="experience_item">
    <time class="date">{{ start_date }}-{{ end_date }}</time>
    <div class="experience_description">
      <h3>{{ role }}</h3>
      <p style=company>{{ company }} [<a :href="full_link">{{ full_link }}</a>]</p>
      <li v-for="item in achievements">
        {{item}}
      </li>
    </div>
  </div>
</template>

<style>

.experience_item {
  display: flex;
  flex-direction: row;
  width: 100%;
  justify-content: left;
  padding-bottom: 20px;
}

.date {
  padding-top: 4px;
}

.experience_description {
  padding-left: 10px;
  flex-direction: column;
  width: 60%;
  justify-content: left;
} 

.company{
  display: flex;
  flex-direction: row
}

</style>
