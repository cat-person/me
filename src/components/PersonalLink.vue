<script>
export default {
  props: ['logo_for', 'link', 'link_txt'],
  setup(props) {
    const getImageUrl = (logo_for) => {
        return new URL(`../assets/${logo_for}_logo.svg`, import.meta.url).href
    }
    return { getImageUrl }
  }
}
</script>

<template>
    <div class="container">
      <img :src="getImageUrl(logo_for)" class="logo"/>
      <a :href="link">{{ link_txt }}</a>
    </div>
</template>

<style scoped>

.container{
  width: fit-content;
  min-width: 16vw;
  display: flex;
  flex-direction: row;
  align-items: center;
}  
.logo {
  height: 16px;
  width: 16px;

}
</style>
