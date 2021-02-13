<template>
  <!-- Must have the app property -->
  <v-app-bar app elevate-on-scroll>

    <router-link :to="{ name: 'home'}">

      <v-toolbar-title>xixxix, llc</v-toolbar-title>

    </router-link>

  </v-app-bar>
</template>

<script>
export default {
  name: 'MainNavigation',

  data: () => ({
    //
  }),
}
</script>
