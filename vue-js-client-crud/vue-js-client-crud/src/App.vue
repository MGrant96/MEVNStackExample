<template>
  <v-app>
    <v-app-bar app dark>
      <div class="d-flex align-center mr-2">
        Tutorial Storage Vault
      </div>
      <v-spacer></v-spacer>
      
      <v-btn to="/tutorials" text>
        Tutorial List
      </v-btn>

      <v-btn to="/add" text>
        Add Tutorial
      </v-btn>
    </v-app-bar>

    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: "app",
};
</script>