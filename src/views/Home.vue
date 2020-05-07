<template>
  <div id="app">
    <LeftNav />
    <Main />
    <Skills />
    <Projects />
    
  </div>
  
</template>

<script>
import Main from '../components/Main.vue'
import LeftNav from "../components/LeftNav.vue"
import Skills from "../components/Skills.vue"
import Projects from "../components/Projects.vue"

export default {
  name: 'Home',
  components: {
    Main,
    LeftNav,
    Skills,
    Projects
  }
}
</script>
