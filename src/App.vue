<template>
  <main class="columns is-gapless is-multiline">
    <div class="column is-one-quarter">
      <BarraLateral />
    </div>
    <div class="column is-three-quarter">
      <FormTop />
    </div>
  </main>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import BarraLateral from './components/BarraLateral.vue';
import FormTop from './components/Formulario.vue';

export default defineComponent({
    name: "App",
    components: {
    BarraLateral,
    FormTop
}
});
</script>

<style>
</style>
