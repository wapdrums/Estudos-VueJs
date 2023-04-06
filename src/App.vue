<template>
  <main class="columns is-gapless is-multiline">
    <div class="column is-one-quarter">
      <BarraLateral>
      </BarraLateral>
    </div>
    <div class="column is-three-quarter">
      <FormularioProjeto></FormularioProjeto>
    </div>
</main>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import BarraLateral from './components/BarraLateral.vue';
import FormularioProjeto from './components/Formulario.vue';

export default defineComponent({
    name: "App",
    components: {
    BarraLateral,
    FormularioProjeto,
}
});
</script>

<style>

</style>
