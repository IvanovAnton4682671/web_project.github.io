<template>
  <HeaderApp></HeaderApp>
  <CompetencyApp></CompetencyApp>
  <SupportApp></SupportApp>
  <RatesApp></RatesApp>

  <CaseApp></CaseApp>
  <FooterApp></FooterApp>
</template>

<script>
  import HeaderApp from '@/components/HeaderApp.vue';
  import CompetencyApp from "@/components/CompetencyApp.vue";
  import SupportApp from "@/components/SupportApp.vue";
  import FooterApp from "@/components/FooterApp.vue";
  import RatesApp from "@/components/RatesApp.vue";
  import CaseApp from "@/components/CaseApp.vue";

  export default
  {
    name: 'App',
    components:
        {
          CaseApp,
          RatesApp,
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