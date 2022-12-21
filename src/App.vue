<template>
  <HeaderApp></HeaderApp>
</template>

<script>
  import HeaderApp from '@/components/HeaderApp.vue'

  export default
  {
    name: 'App',
    components:
        {
          HeaderApp,
        },
  }
</script>

<style>
  #app
  {
    font-family: 'Montserrat', sans-serif;
  }
</style>