<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
        <v-toolbar-title>Random Data Generator</v-toolbar-title>
    </v-app-bar>

    <v-content>
        <DataGenerator />
    </v-content>
  </v-app>
</template>

<script>
import DataGenerator from "@/components/DataGenerator";

export default {
  name: 'App',

  components: {
      DataGenerator
  },

  data: () => ({
    //
  }),
};
</script>
