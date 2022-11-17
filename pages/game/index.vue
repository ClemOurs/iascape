<template>
    <div class="gameIndex">
        <div class="gameIndex-content">
            <div class="container">
                <h1>Bienvenue sur IASCAPE !</h1>
                <p>Tu es sur le point de rentrer dans l’Escape Game. Avant de rentrer, assures toi d’être dans un espace suffisament éclairé et de disposer de suffisament de temps pour compléter les énigmes.</p>
                <TheButton text="commencer" />
                <nuxt-link class="link" to="/">Pas encore prêt ?</nuxt-link>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "IndexGamePage",
    layout: "blank",
}
</script>
