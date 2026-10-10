<script setup>
    window.addEventListener("load", ()=>{
        let bg = document.createElement("img");
        bg.src = "/magimals-games/image/game-logo.jpg";
        bg.alt = "Magimals Games logo.";
	      document.querySelector("#background-grid").appendChild(bg);
    })
</script>
<template>
    <ToxicGrid />
</template>
<style lang="scss">
    /* @use "/assets/scss/toxic-pos.scss"; */
    /* Uncomment this when needed */
</style>
