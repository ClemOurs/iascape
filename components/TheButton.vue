<template>
    <div>
        <button class="button">
            <span class="buttonInside">
                <nuxt-link :to="link"><span class="buttonContent">{{ text }}</span></nuxt-link>
            </span>
        </button>
    </div>
</template>

<script>

export default {
    name: "TheButton",
    props: {
        text: String,
        link: {
            type: String,
            default: ""
        }
    },
}
</script>