<template>
  <div id="app">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        <div class="navbar-header">
          <a class="navbar-brand" href="#">Feedback System</a>
        </div>
        <ul class="nav navbar-nav navbar-right">  
          <li><a href="#" class="btn btn-outline-secondary">Student</a></li>
          <li><button class="btn btn-outline-secondary">logout</button></li>
        </ul>
      </div>
    </nav>
    <lecture-component/>
  </div>
</template>

<script>
import RegisterComponent from './components/RegisterComponent.vue'
import CreateQuizComponent from './components/CreateQuizComponent.vue'
import CourseOverviewComponent from './components/CourseOverviewComponent.vue'
import CourseComponent from './components/CourseComponent.vue'
import CourseLecturesComponent from './components/CourseLecturesComponent.vue'
import LectureComponent from './components/LectureComponent.vue'

export default {
  name: 'app',
  components: {
    RegisterComponent,
    CreateQuizComponent,
    CourseOverviewComponent,
    CourseComponent,
    CourseLecturesComponent,
    LectureComponent
  }
}
</script>

<style scoped>
  .btn {
    margin-left: 5px;
  }
</style>
