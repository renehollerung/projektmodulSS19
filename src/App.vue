<template>
  <div id="app">


    <course-overview-component/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import RegisterComponent from './components/RegisterComponent.vue'
import CreateQuizComponent from './components/CreateQuizComponent.vue'
import CourseOverviewComponent from './components/CourseOverviewComponent.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    RegisterComponent,
    CreateQuizComponent,
    CourseOverviewComponent
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
