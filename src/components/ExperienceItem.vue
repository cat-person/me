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
  <div class="ameow">
    <h4>{{ start_date }} - {{ end_date }}</h4>
    <div class="meowmeow">
      <h3>{{ role }}</h3>
      <p style=company>
        {{ company }} ( <a :href="full_link">{{ full_link }}</a>)
      </p>
      <li v-for="item in achievements">
        {{item}}
      </li>
    </div>
  </div>
</template>

<style>
.ameow{
  display: flex;
  flex-direction: row;
  width: 100%;
  justify-content: left;
}

.company{
  display: flex;
  flex-direction: row
}

.meowmeow{
  flex-direction: column;
  width: 60%;
  justify-content: left;
} 
</style>
