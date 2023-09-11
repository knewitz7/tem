<template>
    <div class="about">
      <h1>Esta é a página sobre a empresa.</h1>
      <Redbutton text="Contato"/>
    </div>
  </template>
  
  <script lang="ts">
  import { defineComponent } from "vue";
  import RedButton from "@/components/RedButton.vue";
  
  export default defineComponent({
    name: "AbountView",
    components:{
      RedButton
    }
  });
  </script>