<script>
export default {
    data() {
        return {
            devAnswer: "AppHeader"
        }
    },

    methods: {

    },

    mounted() {
        console.log("AppHeader.vue montato correttamente");
    }
}
</script>



<template>
    <div id="vHeader">{{ devAnswer }}</div>
</template>



<style scoped>
#vHeader {
    height: 20vh;
    border: 1px dashed red;
}
</style>
