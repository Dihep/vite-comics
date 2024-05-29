<script>
import AppHeader from './components/AppHeader.vue'
export default {
  components: {
    AppHeader
  },

  data() {
    return {
      devAnswer: "Yes"
    }
  },

  methods: {

  },

  mounted() {
    console.log("App.vue montato correttamente");
  }
}
</script>



<template>

  <h1>Funziona?</h1>
  <h2>{{ devAnswer }}</h2>
  <AppHeader/>
  
  
</template>



<style scoped>
  h1 {
    color: red;
  }
  h2 {
    color: green;
  }
</style>
