<template>
  <v-app>
    <!-- <v-app-bar app>
      <v-toolbar-title class="headline text-uppercase">
        <span>Vuetify</span>
        <span class="font-weight-light">MATERIAL DESIGN</span>
      </v-toolbar-title>
      <v-spacer>
        <Header />
      </v-spacer>
      <v-btn text href="https://github.com/vuetifyjs/vuetify/releases/latest" target="_blank">
        <span class="mr-2">Latest Release</span>
      </v-btn>
    </v-app-bar>

    <v-content>
      <HelloWorld />
    </v-content> -->
    <div id="app">
      <Header />
      <router-view />
    </div>
  </v-app>
</template>

<script>
//import HelloWorld from "./components/HelloWorld";
import Header from "./components/layout/Header";

export default {
  name: "App",
  components: {
    Header
  },
  data: () => ({
    //
  })
};
</script>
