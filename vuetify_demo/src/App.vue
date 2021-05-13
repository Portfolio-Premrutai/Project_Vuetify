<template>
  <v-app>
    <!-- div apply class -->
    <v-app-bar app color="primary" dark>
      <v-btn outline @click="$router.push('/')" target="_blank" text>Home</v-btn>

      <v-btn outline @click="$router.push('/about')" target="_blank" text>
        About
        <!-- href="https://github.com/vuetifyjs/vuetify/releases/latest" -->
      </v-btn>
    </v-app-bar>
    <!-- <div>
      <v-toolbar dark prominent src="https://cdn.vuetifyjs.com/images/backgrounds/vbanner.jpg">
        <v-app-bar-nav-icon></v-app-bar-nav-icon>

        <v-toolbar-title>Vuetify</v-toolbar-title>

        <v-spacer></v-spacer>

        <v-btn icon>
          <v-icon>mdi-export</v-icon>
        </v-btn>
      </v-toolbar>
    </div>-->

    <v-content>
      <router-view />
    </v-content>
  </v-app>
</template>

<script>
export default {
  name: "App",

  data: () => ({
    //
  }),
};
</script>
