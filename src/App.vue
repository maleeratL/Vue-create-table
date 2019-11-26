<template>
  <div id="app" class="small-container">
    <h1>Employee</h1>
    <EmployeeTable :employees="employees"/>
  </div>
</template>

<script>
import EmployeeTable from "@/components/EmployeeTable";

export default {
  name: 'app',
  components: {
    EmployeeTable
  },
  data(){
    return{
      employees:[
        {
          id: 1,
          name: 'Kate Smith',
          email: 'kate-smith@gmail.com'
        },
        {
          id: 2,
          name: 'John Lead',
          email: 'jlead@gmail.com'
        }
      ]
    }
  }
}
</script>

<style>
  .small-container{
    max-width: 680px;
  }
</style>
