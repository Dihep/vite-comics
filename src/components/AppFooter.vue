<script>
export default {
    data() {
        return {
            devAnswer: "AppFooter"
        }
    },

    methods: {

    },

    mounted() {
        console.log("AppFooter.vue montato correttamente");
    }
}
</script>



<template>
    <div id="vFooter">{{ devAnswer }}</div>
</template>



<style scoped>
#vFooter {
    height: 20vh;
    border: 1px dashed green;
}
</style>