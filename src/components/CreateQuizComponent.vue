<template> 
    <div> 
       <h1 align= "left"> Feedback System - Quiz - Lehrender <button> Logout </button> </h1> 
       <hr/>
        <body align = "left">
            <strong>Vorlesungsname:</strong> &nbsp; <input type = "text">
                Status: 
                <select name="Status" size="1">
        	        <option>Öffentlich</option>
                    <option>Lesbar</option>
                    <option>Versteckt</option>
                </select>
                <br/>
                <br/>
                Frage 1: <input type="text"> 
                <hr/>
                Antwort 1: <input type="text"> 
                <br/>
                <br/>
                Antwort 2: <input type="text"> 
                <br/>
                <br/>
                <button> Antwort hinzufügen. </button>
                <br/>
                <br/>
                <button> Frage löschen </button> &nbsp; Status: 
                    <select name="Status" size="1">
        	            <option>Öffentlich</option>
                        <option>Lesbar</option>
                        <option>Versteckt</option>
                    </select>
                <hr/>
                <button> neue Frage erstellen </button>
                <br/>
                <br/>
                <br/>
                <br/>
                <button> Zur Vorlesungsübersicht</button>
                &nbsp;
                <button> Schülervorschau </button>
        </body>
    </div>
</template>

<script>
 
</script>

<style>

</style>