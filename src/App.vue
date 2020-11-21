<template>
  <div>

    <v-app>
      <v-app-bar
        app
        color="primary"
        dark
      >

      <v-app-bar-nav-icon></v-app-bar-nav-icon>
      <v-app-bar-title>
        <h1>Address Book</h1>
      </v-app-bar-title>


      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon>mdi-export</v-icon>
      </v-btn>

    </v-app-bar>

    <v-main>

    </v-main>
  </v-app>
  </div>
</template>

<script>


export default {
  name: 'App',

  components: {

  },

  data: () => ({
    //
  }),
};
</script>
