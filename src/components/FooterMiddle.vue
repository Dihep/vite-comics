<script>

export default {
    data() {
        return {
            devAnswer: "FooterMiddle"
        }
    },

    methods: {

    },

    mounted() {
        console.log(DevAnswer+`.vue montato correttamente`);
    }
}
</script>



<template>
    <p>{{ devAnswer }}</p>
</template>



<style scoped>

</style>