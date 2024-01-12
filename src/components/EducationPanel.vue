<script setup>
</script>

<template>
  <h2>Education</h2>
  
  <div class="experience_item">
    <time class="date">Sep 2006 - Jul 2011</time>
    <div class="experience_description">
      <h3>Engineer's degree in Fiber-optic communication</h3>
      <p class="company">Saint Petersburg State University of Aerospace Instrumentation [<a class="company_link" href="https://suai.edu.ru/">suai.edu.ru</a>]</p>
    </div>
  </div>

  <h3 class="courses">Courses</h3>
  <p class="company">
    • Algorithms [<a class="company_link" href="https://www.coursera.org/learn/algorithms-part1">algorithms-part1</a>]
  </p>

  <p class="company">
    • Machine Learning [<a class="company_link" href="https://www.coursera.org/learn/machine-learning">machine-learning</a>]
  </p>

  <p class="company">
    • Google Analytics [<a class="company_link" href="https://analytics.google.com/analytics/academy/course/7">google analytics</a>]
  </p>

  <p class="company">
    • Kotlin [<a class="company_link" href="https://kotlinlang.org/docs/tutorials/koans.html">kotlin koans</a>]
  </p>

  <p class="company">
    • ReactJS [<a class="company_link" href="https://www.codecademy.com/learn/react-102">react 102</a>]
  </p>

  <p class="company">
    • Ruby [<a class="company_link" href="https://www.codecademy.com/learn/learn-ruby">learn-ruby</a>]
  </p>
</template>

<style scoped>
  .experience_item {
    display: flex;
    flex-direction: row;
    width: 100%;
    justify-content: left;
    padding-bottom: 20px;
  }

  .date {
    padding-top: 6px;
  }

  .experience_description {
    padding-left: 20px;
    flex-direction: column;
    width: 80%;
    justify-content: left;
    
  } 

  .company{
    height: 24px;
    font-size: 0.35cm;
    font-family: "MontserratRegular";
  }

  .company_link {
    height: 24px;
    font-size: 0.35cm;
    font-family: "MontserratRegular";
  }

  .courses {
    color: #191970;
    height: 40px;
  }
</style>
