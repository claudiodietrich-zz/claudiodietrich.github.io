<template>
  <div id="app">
    <hero/>
    <intro/>
    <skills/>
  </div>
</template>

<script>
import Hero from '@/components/Hero.vue'
import Intro from '@/components/Intro.vue'
import Skills from '@/components/Skills.vue'

export default {
  name: 'app',
  components: {
    Hero,
    Intro,
    Skills
  }
}
</script>

<style>
#app {
  font-family: 'Open Sans', sans-serif;
}

.title {
  font-family: 'Montserrat', sans-serif;
}

.subtile {
  font-family: 'Open Sans', sans-serif;
}

.has-background-purple {
  background-color: #8C43FF;
}

.has-text-purple {
  color: #8C43FF;
}
</style>
