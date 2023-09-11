<template>
    <aside>
        <Controls />
    </aside>
    <section>
      <div id="couter">Contador: <span id="counterValue">1</span></div>  
    </section>
</template>

<script lang="ts">
import { defineAsyncComponent, defineComponent } from 'vue';
import Controls from '@/components/Controls.vue';

export default defineComponent({
    name: 'MadCounter',
    components: {
        Controls
    }
})
</script>

<style scoped>

</style>