<template>
  <div class="container">
    <h1>Projects</h1>
    <Card v-for="project in products" :key="project.id">



    </Card>
  </div>
</template>

<script>
import Card from '@/components/Card.vue'
export default {
  name: "ProjectsComp",
  components: {
    Card
  }
 

}
</script>

<style>

</style>