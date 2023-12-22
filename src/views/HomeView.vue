<script setup>

import  About from '../components/About.vue'
import  Projects from '../components/Projects.vue'

</script>

<template>
  <main>
    <div class="flex">
    
      <About/>
      <Projects/>


    </div>
  </main>
</template>

<style>
*{
  margin: 0;
  padding: 0;
  overflow: hidden;
}
main{
 
  font-family: 'Montserrat', sans-serif;
  height: 100vh;
  padding: 0 5em;
  margin-top: 4em;
}
h1{
    font-family: 'Montserrat', sans-serif;
    font-size: 2rem;
}
p{
    font-family: 'Montserrat', sans-serif;
  font-size: 16px;
}
.flex{
  display: flex;
  gap: 2em;
  
}
</style>
