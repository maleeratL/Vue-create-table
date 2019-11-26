<template>
  <div id="app">
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
.ma {

}
</style>
