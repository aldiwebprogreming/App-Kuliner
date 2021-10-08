<template>
  <div class="navbar">
  <Navbar />

    <div class="container">
      <h3>Home</h3>
    </div>
  
  </div>
  
</template>


<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'Home',
  components: {
    Navbar
  }
}
</script>
