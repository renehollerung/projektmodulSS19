<template>
    <div>
        <table>
            <tr>
                <th>Kursname</th>
                <th>Semester</th>
                <th>Quiz</th>
                <th>Aktionen</th>
            </tr>

            <tr>
                
            </tr>
        </table>

        <input type="button" value="Neuen Kurz erstellen">

        <ul>
            <li v-for="course in courses">
                <input type="checkbox" name="course" value="course"> {{course.name}}<br>
            </li>
        </ul>
        
        <input type="button" value="Übersicht erstellen">
    </div>
</template>

<script>
export default {
  name: 'OverviewOfCourses',
  props: {
    courses: [{
      name: String
    }]
  }
}
</script>