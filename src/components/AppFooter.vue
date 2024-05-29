<script>
import FooterTop from './FooterTop.vue'
import FooterMiddle from './FooterMiddle.vue'
import FooterBottom from './FooterTop.vue'

export default {
    components: {
        FooterTop,
        FooterMiddle,
        FooterBottom
    },

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
    <div id="vFooter">
        {{ devAnswer }}
        <FooterTop/>
        <FooterMiddle/>
        <FooterBottom/>
        </div>
</template>



<style scoped>
#vFooter {
    height: 20vh;
    border: 1px dashed green;
}
</style>