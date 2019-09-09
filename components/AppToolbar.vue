<template>
  <v-toolbar dark prominent src="/img/lowpoly-green.png">
    <v-spacer />
    <v-badge color="yellow lighten-3" right overlap>
      <template v-slot:badge>
        <v-icon dark>
          mdi-check
        </v-icon>
      </template>
      <v-icon color="white">
        mdi-bell-outline
      </v-icon>
    </v-badge>
  </v-toolbar>
</template>

<script>
export default {}
</script>
