<template>
    <div>
        <button class="button">
        <span class="buttonInside">
            <span class="buttonContent">{{ text }}</span>
        </span>
        </button>
    </div>
</template>

<script>
export default {
    name: "TheButton",
    props: {
        text: String
    },
}
</script>