<script>
import { ref } from 'vue'
export default {
  props: ['start_date', 'end_date', 'role', 'company', 'company_link', 'achievements'],
  setup(props) {
    const skills = ref([
    "Android SDK", 
    "iOS SDK", 
    "Flutter",
    "React-native",
    "Kotlin", 
    "Swift", 
    "Rust", 
    "Java", 
    "C#",
    "JS", 
    "Dart", 
    "Rest API",  
    "SRT", 
    "KTOR",
    "Jetpack Compose",
    "SwiftUI",
    "WebSocket", 
    "WebGPU", 
    "Blender", 
    "Sketch",
    "Git", 
    "Test Automation"
    ])

    return { skills }
  }
}
</script>

<template>
    <div class="skills">
      <h2>Skills</h2>
      <h4 v-for="skill in skills">
        {{skill}}
      </h4>
    </div>
</template>

<style scoped>
h2 {
  color: #FFFFFF;
  padding-bottom: 6px;
}
h4 {
  height: 20px;
  color: #FFFFFF;
}
.skills{
  flex-direction: column;
  width: 100%;
  justify-content: left;
}  
</style>
