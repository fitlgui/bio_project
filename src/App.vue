<template>
  <body>
    <menu-bio></menu-bio>  
  </body>
</template>

<script>
import menuBio from './components/Home.vue'

export default {
  name: 'App',
  components: {
    menuBio
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  scroll-behavior: smooth;
}

body{
  width: 100%;
  height: 100vh;
}

</style>
