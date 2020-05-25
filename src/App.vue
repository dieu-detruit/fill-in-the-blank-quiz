<template>
  <v-app>
    <v-toolbar dark>
      <v-avatar>
        <v-img src="@/assets/gyoza.png" height="128px" width="128px"></v-img>
      </v-avatar>
      <v-toolbar-title>保育所保育方針</v-toolbar-title>

      <v-spacer></v-spacer>

    </v-toolbar>
    <v-container class="green lighten-5" style="height: 90vh;">
      <v-layout align-center justify-center fill-height>
        <Question></Question>
      </v-layout>
    </v-container>
  </v-app>
</template>

<script>
import Question from './components/Question';

export default {
  name: 'App',

  components: {
    Question,
  },

  data: () => ({
    //
  }),
};
</script>
