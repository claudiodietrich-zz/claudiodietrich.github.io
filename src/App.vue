<template>
  <div id="app">
    <hero/>
    <intro/>
  </div>
</template>

<script>
import Hero from '@/components/Hero.vue'
import Intro from '@/components/Intro.vue'

export default {
  name: 'app',
  components: {
    Hero,
    Intro
  }
}
</script>

<style>
.title {
  font-family: 'Montserrat', sans-serif;
}

.subtile {
  font-family: 'Open Sans', sans-serif;
}
.has-background-purple {
  background-color: #8C43FF;
}
</style>
