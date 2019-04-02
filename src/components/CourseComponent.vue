<template>
    <div class="container" id="courses">
        <table class="table table-hover">
            <thead>
                <tr>
                    <th scope="col">Kursname</th>
                    <th scope="col">Semester</th>
                    <th scope="col">Status</th>
                    <th scope="col">Registrieren</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Grundlagen der Programmierung 1</td>
                    <td>WS 18/19</td>
                    <td>7/8</td>
                    <a href="#" class="btn btn-success btn-block btn-sm">Einschreiben</a>
                </tr>
                <tr>
                    <td>Entwicklung verteilter Anwendungen</td>
                    <td>WS 18/19</td>
                    <td>4/7</td>
                    <a href="#" class="btn btn-danger btn-block btn-sm">Ausschreiben</a>
                </tr>
                <tr>
                    <td>Kommunikationssysteme</td>
                    <td>WS 18/19</td>
                    <td>6/7</td>
                    <a href="#" class="btn btn-danger btn-block btn-sm">Ausschreiben</a>
                </tr>
            </tbody>
        </table>
        <div class="card">
            <div class="card-body">
                <div class="form-check">
                    <input class="form-check-input" type="checkbox" value="" id="defaultCheck1">
                    <label class="form-check-label" for="defaultCheck1">Kurs 2</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="checkbox" value="" id="defaultCheck2">
                    <label class="form-check-label" for="defaultCheck2">Kurs 3</label>
                </div>
                <button class="btn btn-secondary">Übersicht erstellen</button>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    #courses {
        margin-top: 20px;
    }

    .btn {
        margin-top: 10px;
    }
</style>


