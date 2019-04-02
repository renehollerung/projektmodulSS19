<template>
    <div class="container">
        <table class="table table-hover" id="courses">
            <thead>
                <tr>
                    <th scope="col">Vorlesungen</th>
                    <th scope="col">Lernstatus</th>
                    <th scope="col">Feedback</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Vorlesung 1</td>
                    <td>100%</td>
                    <a href="#" class="btn btn-success btn-block btn-sm">abgeben</a>
                </tr>
                <tr>
                    <td>Vorlesung 2</td>
                    <td>80%</td>
                    <a href="#" class="btn btn-success btn-block btn-sm">abgeben</a>
                </tr>
                <tr>
                    <td>Vorlesung 3</td>
                    <td>unbeantwortet</td>
                    <a href="#" class="btn btn-danger btn-block btn-sm">abgeben</a>
                </tr>
            </tbody>
        </table>
        <button class="btn btn-secondary">Zurück zur Übersicht</button>
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


