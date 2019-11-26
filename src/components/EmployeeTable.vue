<template>
    <div id="employee-table">
        <table>
            <thead>
                <tr>
                    <th>Employee name</th>
                    <th>Employee email</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Kate Smith</td>
                    <td>kate-smith@gmail.com</td>
                </tr>
                <tr>
                    <td>John Lead</td>
                    <td>jlead@gmail.com</td>
                </tr>
            </tbody>
        </table>
    </div>
</template>

<script>
    export default {
        name: "employee-table"
    }
</script>

<style scoped>
    table {
        font-family: "Trebuchet MS", Arial, Helvetica, sans-serif;
        border-collapse: collapse;
        width: 100%;
    }

    table td, table th {
        border: 1px solid #ddd;
        padding: 8px;
    }

    table tr:nth-child(even){background-color: #f2f2f2;}

    table tr:hover {background-color: #ddd;}

    table th {
        padding-top: 12px;
        padding-bottom: 12px;
        text-align: left;
        background-color: #4CAF50;
        color: white;
    }
</style>