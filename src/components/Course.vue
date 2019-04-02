<template>
    <div>
        <td>{{course.name}}}</td>
        <td>{{course.semester}}</td>
        <td>{{course.quiz}}</td>
        <td>
            <input type="button" value="Bearbetien">
            <input type="button" value="Löschen">
        </td>
    </div>
</template>


<script>
export default {
  name: 'Course',
  props: {
    course: {
      name: String,
      semester: String,
      quiz: int
    }
  }
}
</script>