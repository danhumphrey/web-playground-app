<template>
  <v-app>
    <v-app-bar app color="dark" dark>
      <div class="d-flex align-center">
        <v-img
          alt="Web Playground - icon by panyawut norrasing from the Noun Project"
          class="shrink mr-2"
          contain
          src="./assets/logo.png"
          transition="scale-transition"
          width="259"
        />
      </div>

      <v-spacer></v-spacer>

      <v-btn
        href="https://github.com/danhumphrey/web-playground-app"
        target="_blank"
        icon

      >
        <v-icon>mdi-github</v-icon>
      </v-btn>
    </v-app-bar>

    <v-main>
      <Home msg="Welcome to the Web Playground" />
    </v-main>
  </v-app>
</template>

<script>
import Home from "./components/Home";

export default {
  name: "App",

  components: {
    Home
  },

  data: () => ({
    //
  })
};
</script>
