<template>
    <div class="home">
        <Counter msg="CONTADEIRO" />
    </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import Counter from "@/components/Counter.vue"; // @ is an alias to /src

export default defineComponent ({
    name: "HomeView",
    components: {
        Counter,
    },
});
</script>