<template>
    <article>
        <!-- <img src="" alt="img card"> -->
        <div class="placeholder"></div>
        <div class="contentCard">
            <h4>Title</h4>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Harum, saepe!</p>
        </div>
    </article>
</template>

<style lang="scss" scoped>
    @import '~/assets/styles/abstracts/__variables.scss';

    article {
        width: 30%;
        height: 350px;
        display: flex;
        flex-direction: column;
        justify-content: space-between;

        .contentCard {
            position: relative;
            padding: 2em;
            color:$white;
            background: $gradient;
            h4 {
                font-size: 2em;
                margin-bottom: 10px;
            }
            p {
                font-size: 1.3em;
            }
            &::before {
                content: '';
                position: absolute;
                left: 0; bottom: 0;
                width: 16px; 
                height: 16px;
                background-color: $white;
            }
            &::after {
                content: '';
                position: absolute;
                right: 0; bottom: 0;
                width: 0; 
                height: 0; 
                border-left: 16px solid transparent;
                border-bottom: 16px solid $white;
            }
        }
        .placeholder {
            background-color: $grey;
            height: 76%;
        }
    }
</style>