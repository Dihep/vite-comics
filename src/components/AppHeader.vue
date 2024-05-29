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
    <nav>
        <div id="navLogo"><img src="../assets/dc-logo.png" alt=""></div>
        <ul>
            <li>CHARACHTERS</li>
            <li>COMICS</li>
            <li>MOVIES</li>
            <li>TV</li>
            <li>GAMES</li>
            <li>COLLECTIBLES</li>
            <li>VIDEOS</li>
            <li>FANS</li>
            <li>NEWS</li>
            <li>SHOP</li>
        </ul>
    </nav>
</template>



<style scoped>
nav {
    height: 10vh;
    padding: 0 15vw;
    margin: 0 auto;
    background-color: white;
    color: rgb(30, 30, 30);
    display: flex;
    justify-content: space-between;
    align-items: center;
}
#navLogo {
    width: 30%;
}
ul {
    list-style: none;
    display: flex;
    gap: 1rem;
    width: 70%;
}
img {
    height: 8vh;
}
</style>
