<script>
import { ref } from 'vue'
export default {
  setup() {
    const icon = new URL(`../assets/pdf_download.svg`, import.meta.url).href
    return { icon }
  }
}
</script>

<template>
  <div>
    <img :src="icon" class="logo"/>
    <a href="../assets/Senior_Software_Developer_Aleksei_Klyshnikov.pdf" download>Download PDF</a>
  </div>
</template>

<style scoped>
.logo {
  height: 24px;
  width: 24px;
  padding-right: 4px;
}
</style>
