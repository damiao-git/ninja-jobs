<template>
  <h1>Job Details Page</h1>
  <p>The job id is {{ id }}</p>
</template>

<script>
export default {
  props: ['id'],
  // data() {
  //   return {
  //     id: this.$route.params.id // colect the id from route /jobs/:id  and attribute to id variable
  //   }
  // }
}
</script>

<style></style>