<template>
  <HeaderApp></HeaderApp>
  <BodyApp></BodyApp>
  <FooterApp></FooterApp>
</template>

<script>
  import HeaderApp from '@/components/HeaderApp.vue';
  import BodyApp from "@/components/BodyApp.vue";
  import FooterApp from "@/components/FooterApp.vue";

  export default
  {
    name: 'App',
    components:
        {
          FooterApp,
          HeaderApp,
          BodyApp,
        },
  }
</script>

<style>
  #app
  {
    font-family: 'Montserrat', sans-serif;
  }
</style>