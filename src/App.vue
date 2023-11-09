<template>
  <div class="container">
    <AppHeader />
  </div>
    <AppMainContent />
    <AppFooter />
  
</template>

<script>
  import AppHeader from './components/AppHeader.vue'
  import AppMainContent from './components/AppMainContent.vue'
  import AppFooter from './components/AppFooter.vue'

  export default {
    components: {
      AppHeader,
      AppMainContent,
      AppFooter
    },
  }
</script>

<style lang="scss" scoped>

</style>