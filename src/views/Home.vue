<template>
  <div class="home">
    <img alt="image" class="image" src="../assets/image.jpg">
    <FirstComponent msg="Проверяем работу polyfill, babel, vuetify"/>
  </div>
</template>

<script>
// @ is an alias to /src
import FirstComponent from '@/components/FirstComponent.vue'

export default {
  name: 'home',
  components: {
      FirstComponent
  }
}
</script>
<style scoped>
  .image{
  max-width:400px;
  height:auto;
  }
</style>