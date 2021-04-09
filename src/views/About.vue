<template>
  <div class="d-block">
    <v-parallax
      dark
      height="300"
      src="https://miro.medium.com/max/3840/1*5CSpRoGap926QIsxfwH9Nw.jpeg"
    >
      <v-row align="center" justify="center">
        <v-col class="text-center" cols="12">
          <h1 class="display-1 subheading mb-4">Single Page Application</h1>
          <h4 class="font-weight-thin">S P A</h4>
        </v-col>
      </v-row>
    </v-parallax>
    <div class="container">
      <br />
      <h1>Aplicación de página única</h1>
      <v-divider></v-divider>
      <br />
      <div>
        <p class="text-justify">
          Es la traduccion de SPA y está es una aplicación web o es un sitio web
          que cabe en una sola página con el propósito de dar una experiencia
          más fluida a los usuarios, como si fuera una aplicación de escritorio.
          En un SPA todos los códigos de HTML, JavaScript, y CSS se cargan una
          sola vez o los recursos necesarios se cargan dinámicamente cuando lo
          requiera la página, normalmente como respuesta a las acciones del
          usuario.
        </p>
      </div>
      <br />
      <v-container>
        <v-row>
          <v-col>
            <div></div>
            <v-img
              contain
              max-height="450"
              max-width="550"
              src="https://i.pinimg.com/originals/e4/26/70/e426702edf874b181aced1e2fa5c6cde.gif"
            ></v-img>
          </v-col>
          <v-col align-self="center">
            <div>
              <h2 class="text-center">Estás en un SPA hecho por mi</h2>
              <v-divider></v-divider>
              <br />
            </div>
            <p class="text-justify">
              Esta página lleva aproximadamente un tiempo de desarrollo de 11
              horas y contando, se está utilizando el framework de diseño
              llamado Vuetify. El tiempo de desarrollo de esta apicación (solo
              Front-End) fue reducido gracias a los templates de este framework
              el cual está basado en material design. Cabe mencionar que
              Material design es un concepto de diseño implementado por google
              en sus aplicaciones para android.
            </p>
          </v-col>
        </v-row>
      </v-container>
    </div>
  </div>
</template>
