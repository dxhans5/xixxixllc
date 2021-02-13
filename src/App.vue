<template>
  <v-app>
    <MainNavigation></MainNavigation>

    <v-main>
      <router-view></router-view>
    </v-main>
  </v-app>
</template>

<script>

import MainNavigation from "@/components/MainNavigation";
export default {
  name: 'App',

  components: {MainNavigation},

  data: () => ({
    //
  }),
};
</script>
