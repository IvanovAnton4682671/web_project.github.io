<template>
  <HeaderApp></HeaderApp>
  <CompetencyApp></CompetencyApp>
  <SupportApp></SupportApp>
  <FooterApp></FooterApp>
</template>

<script>
  import HeaderApp from '@/components/HeaderApp.vue';
  import CompetencyApp from "@/components/CompetencyApp.vue";
  import SupportApp from "@/components/SupportApp.vue";
  import FooterApp from "@/components/FooterApp.vue";

  export default
  {
    name: 'App',
    components:
        {
          HeaderApp,
          CompetencyApp,
          SupportApp,
          FooterApp,
        },
  }
</script>

<style>
  #app
  {
    font-family: 'Montserrat', sans-serif;
  }
</style>