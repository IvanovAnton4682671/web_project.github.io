<template>
  <HeaderApp></HeaderApp>
  <CompetencyApp></CompetencyApp>
  <SupportApp></SupportApp>
  <RatesApp></RatesApp>
  <TimeApp></TimeApp>
  <TeamApp></TeamApp>
  <CaseApp></CaseApp>


  <FaqApp></FaqApp>
  <FooterApp></FooterApp>
</template>

<script>
  import HeaderApp from '@/components/HeaderApp.vue';
  import CompetencyApp from "@/components/CompetencyApp.vue";
  import SupportApp from "@/components/SupportApp.vue";
  import RatesApp from "@/components/RatesApp.vue";
  import TimeApp from "@/components/TimeApp.vue";
  import TeamApp from "@/components/TeamApp.vue"
  import CaseApp from "@/components/CaseApp.vue";
  import FooterApp from "@/components/FooterApp.vue";
  import FaqApp from "@/components/FaqApp.vue";

  export default
  {
    name: 'App',
    components:
        {
          FaqApp,
          HeaderApp,
          CompetencyApp,
          SupportApp,
          RatesApp,
          TimeApp,
          TeamApp,
          CaseApp,
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