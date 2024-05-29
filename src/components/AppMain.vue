<script>
export default {
    data() {
        return {
            devAnswer: "AppMain"
        }
    },

    methods: {

    },

    mounted() {
        console.log("AppMain.vue montato correttamente");
    }
}
</script>



<template>
    <div id="mainContainer">
        <h1>--> Content goes here <--</h1>
    </div>
    
</template>



<style scoped>
#mainContainer {
    height: 20vh;
    background-color: rgb(30, 30, 30);
    color: white;
    padding: 0 2rem;
}
h1{
    position: relative;
    top: 35%;
}
</style>