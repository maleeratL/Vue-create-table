<template>
  <div id="app" class="small-container">
    <h1>Employee</h1>
    <EmployeeTable/>
  </div>
</template>

<script>
import EmployeeTable from "@/components/EmployeeTable";

export default {
  name: 'app',
  components: {
    EmployeeTable
  }
}
</script>

<style>
  .small-container{
    max-width: 680px;
  }
</style>
