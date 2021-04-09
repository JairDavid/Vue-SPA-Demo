<template>
  <v-card class="ma-5" max-width="344">
    <v-img
      src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
      height="200px"
    ></v-img>

    <v-card-title>{{title}}</v-card-title>

    <v-card-subtitle>{{subtitle}}</v-card-subtitle>

    <v-card-actions>
      <v-btn color="orange lighten-2" text> Explore </v-btn>

      <v-spacer></v-spacer>
    </v-card-actions>
  </v-card>
</template>
<script>
export default {
  name: "Tarjeta",
  data:()=>({
    title:"Titulo del card en pantalla",
    subtitle:"Subtitulo del card en pantalla"
  }),
  methods:{
    //
  }
};
</script>