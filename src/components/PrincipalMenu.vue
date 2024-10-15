<template>
    <div class="principal-text">
        <p>Presione un botón para acceder a una API</p>
    </div>

    <div class="menu">
        <ButtonsApi label="asadasd" />
        <ButtonsApi label="a" />
        <ButtonsApi label="a" />
        <ButtonsApi label="a" />

    </div>

</template>

<script>

import ButtonsApi from './ButtonsApi.vue';

export default {
    name: 'PrincipalMenu',
    components: {
        ButtonsApi
    }
}

</script>

<style>
    .principal-text {
        height: 75%;
        width: 75%;
        background-color: black;
        padding: auto;
        color: rgb(0, 255, 162);
    }
</style>