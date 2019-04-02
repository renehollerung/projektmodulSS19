<template>
  <div>
    <p>Eingeschrieben Studenten:</p>

    <ul>
      <li v-for="st in students" >{{st.name}}</li>
    </ul>
    <input type="button" value="Zurück zur Übersicht">
  </div>
</template>



<script>
export default {
  name: 'SgndStudList',
  props: {
    students: {
      name: String
    }
  }
}
</script>