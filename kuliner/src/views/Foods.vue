<template>
  <div class="navbar">
  <Navbar />

    <div class="container">
      <h3>Foods</h3>
    </div>
  
  </div>
  
</template>


<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'Foods',
  components: {
    Navbar
  }
}
</script>
