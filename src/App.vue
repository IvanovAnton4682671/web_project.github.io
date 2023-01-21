<template>
  <HeaderApp></HeaderApp>
  <CompetencyApp></CompetencyApp>
  <SupportApp></SupportApp>
  <RatesApp></RatesApp>
  <TimeApp></TimeApp>
  <TeamApp></TeamApp>
  <CaseApp></CaseApp>
  <SliderApp></SliderApp>
  <RingsApp></RingsApp>
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
  import SliderApp from "@/components/SliderApp.vue";
  import RingsApp from "@/components/RingsApp.vue"
  import FaqApp from "@/components/FaqApp.vue";
  import FooterApp from "@/components/FooterApp.vue";

  export default
  {
    name: 'App',
    components:
        {
          HeaderApp,
          CompetencyApp,
          SupportApp,
          RatesApp,
          TimeApp,
          TeamApp,
          CaseApp,
          SliderApp,
          RingsApp,
          FaqApp,
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