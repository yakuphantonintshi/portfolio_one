<template>
  <div class="home">
    <h2>Home</h2>
    <img :src= image class="picture">
    
  </div>
</template>

<script>


export default {
  name: 'HomeView',
  data(){
    return{
      image: 'https://yakuphantonintshi.github.io/myimages/Images/my_picture2.jpg'
    }
  }
}
</script>
<style scoped>
.picture{
  width: 18rem;
}

</style>
