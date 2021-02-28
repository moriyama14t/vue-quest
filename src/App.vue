<template>
    <v-app>
        <v-toolbar
          color="blue"
          max-height="60"
        >
          <v-toolbar-title style="color:white" >YouTube Curation</v-toolbar-title>
        </v-toolbar>
        <top />
        <v-toolbar
          src="https://cdn.vuetifyjs.com/images/backgrounds/vbanner.jpg"
        >
          <v-spacer />
          <p style="color:white">@QuestAcademia</p>
        </v-toolbar>
    </v-app>
</template>

<script>
import Top from './components/Top.vue'

export default {
    name: 'App',
      components: {
        Top,
      },
  }
</script>


