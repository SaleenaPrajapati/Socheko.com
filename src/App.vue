<template>
<div id="app">
  <!-- <button class="button is-primary">This is a button</button> -->
  <NavBar />
</div>
</template>

<script>
import NavBar from "@/components/NavBar.vue"

 export default {
  name: 'App',
  components: {
    NavBar
  }
  }
</script>

<style lang="scss">

@import 'buefy/dist/buefy.css';



</style>
