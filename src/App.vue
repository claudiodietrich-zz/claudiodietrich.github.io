<template>
  <div id="app">
    <Intro/>
  </div>
</template>

<script>
import Intro from '@/components/Intro.vue'

export default {
  name: 'app',
  components: {
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
</style>
