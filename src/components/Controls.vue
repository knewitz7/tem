<template>
    <button>
        <span class="icon">
            <i class="fas fa-play"></i>
        </span>
        <span>Play</span>
    </button>
    <button>
        <span class="icon">
            <i class="fas fa-pause"></i>
        </span>
        <span>Pause</span>
    </button>
    <button>
        <span class="icon">
            <i class="fas fa-stop"></i>
        </span>
        <span>Stop</span>
    </button>
</template>

<script lang="ts"> 
import { DefineComponent, defineComponent } from 'vue';

export default defineComponent ({
    name: 'Controls',

});
</script>

<style scoped>
button { cursor: pointer; padding: 20px 40px; }
button span { margin: 5px; }
</style>