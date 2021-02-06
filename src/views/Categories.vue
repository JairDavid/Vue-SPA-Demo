<template>
  <div class="container">
    <br>
    <h2 class="text-center">Categorias disponibles</h2>
    <v-divider></v-divider>
    <br>
    <v-container>
      <v-layout row>
        <Tarjeta />
        <Tarjeta />
        <Tarjeta />
        <Tarjeta />
        <Tarjeta />
        <Tarjeta />
        <Tarjeta />
        <Tarjeta />
        <Tarjeta />
      </v-layout>
    </v-container>
  </div>
</template>
<script>
import Tarjeta from "../components/Tarjeta.vue";
export default {
  components: {
    Tarjeta,
  },
};
</script>