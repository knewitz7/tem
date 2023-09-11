<!-- Bloco de código HTML reaproveitável -->
<template>
    <div>
        <button>{{ text }}</button>
    </div>
</template>

<!-- Lógica/Comportamento do componente, em TypeScript -->
<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
    name: 'RedButton',
    props: {
        text: String;
    }
});
</script>

<!-- Estilos do componente, em CSS -->
<style>
button {
    background-color: #A00;
    color: white;
    border-radius: 5px;
    cursor: pointer;
    border: solid 1px black;
    font-weight: bold;
    margin: 30px;
    padding: 15px 30px;
    font-size: 20px;
    text-transform: uppercase;
    width: 300px;
}
button:hover {
    background-color: red;
}
</style>