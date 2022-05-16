<template>
<div id="app">
  <!-- <button class="button is-primary">This is a button</button> -->
  <NavBar />
  <HeaderItem />
</div>
</template>

<script>
import NavBar from "@/components/NavBar.vue"
import HeaderItem from "@/components/HeaderItem.vue"

 export default {
  name: 'App',
  components: {
    NavBar,
    HeaderItem
  }
  }
</script>

<style lang="scss">

@import 'buefy/dist/buefy.css';



</style>
