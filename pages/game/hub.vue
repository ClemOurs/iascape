<template>
    <section class="hub">
        <div class="hub-side">
            <h3>Bienvenue sur IASCAPE !</h3>
            <p>Parcourez les énigmes de l’escape game par axes.</p>
        </div>
        <div class="hub-links">
            <div class="container">
                <span>
                    <div></div>
                    <nuxt-link class="link" to="/game/enigmas/crea">Axe Création et Design</nuxt-link>
                </span>
                <span>
                    <div></div>
                    <nuxt-link class="link" to="/game/enigmas/dev">Axe Coding & Digital Innovation</nuxt-link>
                </span>
                <span>
                    <div></div>
                    <nuxt-link class="link" to="/game/enigmas/videogame">Axe Jeux Vidéo</nuxt-link>
                </span>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "IndexPage",
    layout: "blank",
}
</script>
