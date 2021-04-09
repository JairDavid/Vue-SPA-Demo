<template>
  <v-app>
    <v-app-bar app color="secondary" dark>
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          height="100"
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-logo-dark.png"
          transition="scale-transition"
          width="40"
        />
        <div>
          <h1>Vuetify</h1>
        </div>
      </div>
      <v-spacer></v-spacer>
      <v-btn elevation="5" rounded class="ma-1" @click="home()"
        ><v-icon left>home</v-icon>Inicio
      </v-btn>
      <v-btn elevation="5" rounded class="ma-1" @click="explore()"
        ><v-icon left>explore</v-icon> Explorar
      </v-btn>
      <v-btn elevation="5" rounded class="ma-1" @click="categories()"
        ><v-icon left>local_offer</v-icon> Categorias
      </v-btn>
      <v-btn elevation="5" rounded class="ma-1" @click="about()"
        ><v-icon left>info</v-icon> Acerca de
      </v-btn>
    </v-app-bar>
    

    <v-main>

      <router-view> </router-view>

    </v-main>


    <div>
      <v-footer padless color="dark">
        <v-col class="text-center" cols="12">
          <strong style="color: white"
            >@Todos los derechos reservados — {{ new Date().getFullYear() }}
          </strong>
        </v-col>
      </v-footer>
    </div>
  </v-app>
</template>
<script>
export default {
  name: "Menu",
  methods: {
    home() {
      this.$router.push("/");
    },
    about() {
      this.$router.push("/about");
    },
    categories() {
      this.$router.push("/categories");
    },
    explore() {
      this.$router.push("/explore");
    },
  },
};
</script>