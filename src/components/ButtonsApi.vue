<template>
<div class="button-style">
    <button @click="buttonPress" class="button-details">{{ label }}</button>
</div>
</template>

<script>

export default {
    methods: {
        buttonPress: function() {
                console.log(apis[0]);
        }
    }
};
let apis = 
["https://countriesnow.space/api/v0.1/countries/population",
 "https://api.jikan.moe/v4/recommendations/anime",
 "https://api.jikan.moe/v4/random/anime",
 "https://api.jikan.moe/v4/random/manga"]

</script>

<style>
    .button-style {
        height: 75%;
        width: 75%;
        background-color: rgb(3, 102, 38);
        padding: auto;
        color: rgb(0, 255, 162);
    }

    .button-details {
        background-color: rgb(0, 255, 162);
        color: rgb(0, 0, 0);
        padding: 15px 32px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        margin: 4px 2px;
        cursor: pointer;
    }
</style>