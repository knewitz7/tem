<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    
    <h3>Instituto Evoluir</h3>
    <RedButton text="Entrar"/>
    <RedButton text="Cadastrar"/>
    <RedButton text="Sair"/>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import RedButton from "@/components/RedButton.vue";

export default defineComponent({
  name: 'Counter',
  props: {
    msg: String,
  },
});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
