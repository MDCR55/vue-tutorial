<template>
    <div class="our-help">
        <h1>{{ pageName }}</h1>
        <p>{{ pageDesc }}</p>
    </div>
</template>

<script>
export default {
    data: function() {
        return {
            pageName: "Help",
            pageDesc: "This is help us page"
        };
    },
    name: "help"
};
</script>
