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
    <div id="vMain">{{ devAnswer }}</div>
</template>



<style scoped>
#vMain {
    height: 20vh;
    border: 1px dashed blue;
}
</style>