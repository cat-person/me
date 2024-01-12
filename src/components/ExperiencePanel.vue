<script setup>
import ExperienceItem from './ExperienceItem.vue';
</script>

<template>
  <h2>Experience</h2>
  
  <ExperienceItem 
    start_date="Jan 2023" 
    end_date="Oct 2023"
    role="Senior Software Developer"
    company="Freelance"
    company_link="upwork.com"
    :achievements="[
      'Created Video streaming App for Android working with SRT / Rest API', 
      'Implemented UI using Jetpack Compose', 
      'Implemented Amplitude analytics'
    ]"/>
  
  <ExperienceItem 
    start_date="Feb 2022" 
    end_date="Sep 2022"
    role="Product Manager"
    company="MetaMap"
    company_link="metamap.com"
    :achievements="[
      'Reworked analytics', 
      'Introduced AB testing', 
      'Introduced test automation for Mobile platforms'
    ]"/>

  <ExperienceItem 
    start_date="Dec 2020" 
    end_date="Feb 2022"
    role="Senior Mobile Developer"
    company="MetaMap"
    company_link="metamap.com/"
    :achievements="[
      'Modernised application by rewriting it to Kotlin', 
      'Implemented UI for document upload', 
      'Fixed memory leaks and thousands of other issues',
      'Reworked camera fragment inside the app to make it work across wide range of devices'
    ]"/>
  
  <ExperienceItem 
    start_date="Oct 2015" 
    end_date="Nov 2019"
    role="Lead Android Developer"
    company="Job Today"
    company_link="jobtoday.com/"
    :achievements="[
      'Worked on Android Application with Chat, Searchable lists, Monetisation etc', 
      'Communicated with stakeholders in order to implement the best UX', 
      'Was responsible for App releases'
    ]"/>

  <ExperienceItem 
    start_date="Feb 2011" 
    end_date="Oct 2015"
    role="Android Software Engineer"
    company="Touch Instinct"
    company_link="touchinstinct.com/"
    :achievements="[
      'Worked on plethora of mobile applications from mobile cinema to budget tracking app to mobile games and mini social network.'
    ]"/>

  <ExperienceItem 
    start_date="Nov 2010" 
    end_date="Dec 2011"
    role="Junior Programmer"
    company="Russian Institute of Power Radiobuilding"
    company_link="rimr.ru"
    :achievements="[
      'Implemented UI for longwave radiostation control', 
      'Implemented communication protocol with external devices', 
    ]"/>
  
  </template>

<style scoped>

</style>
