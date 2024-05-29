<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter
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

  <AppHeader/>
  <AppMain/>
  <AppFooter/>

</template>



<style scoped>
  h1 {
    color: red;
  }
  h2 {
    color: green;
  }
</style>
