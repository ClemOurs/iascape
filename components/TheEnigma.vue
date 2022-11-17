$
<template>
    <div class="enigmaCard">
        <div class="enigmaCard-content">
            <h1>{{title}}</h1>
            <p>{{text}}</p>
            <div class="tags">
                <div class="tag">
                    <img src="~/assets/enigmas_logos/Timelapse.svg" alt="logo">
                    <p>{{time}} minutes</p>
                </div>
                <div class="tag">
                    <img src="~/assets/enigmas_logos/Extension.svg" alt="logo">
                    <p>Difficulté {{difficulty}}</p>
                </div>
                <div class="tag">
                    <img src="~/assets/enigmas_logos/Verified.svg" alt="logo">
                    <p>Enigme officielle</p>
                </div>
            </div>
            <div class="buttons">
                <TheButton text="commencer" />
                <button class="howPlay">
                    comment jouer ?
                </button>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "TheEnigma",
    props: {
        title: String,
        difficulty: String,
        time: String,
        text: String
    }
}
</script>

<style lang="scss" scoped>

@import '~/assets/styles/abstracts/__variables.scss';
    .enigmaCard {
        height: 900px;
        background-image: url('~/assets/grid.png');
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        display: flex;
        align-items: center;
        &-content {
            padding: 2em;
            width: 80%;
            margin: 0 auto;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 50px;
            h1 {
                font-size: 3.5em;
                color: $secondary;
            }
            p {
                color: $grey;
                font-size: 1.3em;
                line-height: 25px;
                font-weight: 300;
                text-justify: justify;
            }
        }
        .tags {
            display: flex;
            flex-wrap: wrap;
            gap: 120px;
            
            .tag {
                gap:5px;
                p {
                    font-size: 1em;
                    line-height: none; 
                }
            }
        }
        .tag, .buttons {
            display: flex;
            flex-direction: row;
            align-items: center;
        }
        .buttons {
            gap: 50px;
        }
        .howPlay {
            padding: 1em 2em;
            color: $grey;
            border: 1px solid $white;
        }
    }
</style>