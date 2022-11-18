<template>
    <div class="introGame">
        <div class="introGame-content">
            <article>
                <h1>Découvrez l’univers d’IASCAPE</h1>
                <p>IASCAPE est un Escape Game en ligne qui propose aux lycéens et futurs étudiants de découvrir différents axes de l’école IIM. Vous parcourez dans un univers numérique où vous devrez combattre une intelligence artificielle qui a décidé de s’en prendre à l’école et à ses travaux.</p>
                <section class="video">
                    <div class="video-border">
                        <div class="video-content"></div>
                    </div>
                </section>
            </article>
            <TheButton text="continuer" link="/game/hub" />
        </div>
    </div>
</template>

<script>
export default {
    name: "IndexGamePage",
    layout: "blank",
}
</script>
