<template>
<div>
    <h1 align = "left"> Feedback System - Kursname </h1> 
    <hr/>
<body>
    <br/>
<table align = "center">
  <tr>
    <th>Vorlesungen</th>
    <th>Fragenanzahl</th>
    <th>Quiz</th>
  </tr>
  <tr>
    <td>Vorlesung1</td>
    <td>5</td>
    <td>
        <button> bearbeiten </button> &nbsp; <button> löschen </button> &nbsp; <button> Statistik anzeigen </button>
    </td>
  </tr>
  <tr>
    <td>Vorlesung2</td>
    <td>4</td>
    <td>
        <button> bearbeiten </button> &nbsp; <button> löschen </button> &nbsp; <button> Statistik anzeigen </button>
    </td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>
<br/>
    <button> neues Quiz erstellen </button>
<br/>
<br/>
<br/>
    <button> Gesamtstatistik anzeigen </button> &nbsp; <button> Teilnehmer anzeigen </button>
<br/>
<br/>
    Status: <select name="Status" size="1">
        	        <option>Öffentlich</option>
                    <option>Lesbar</option>
                    <option>Versteckt</option>
            </select>
<br/>
<br/>
    <button> zurück zur Übersicht </button>
</body>

</div>
</template>
