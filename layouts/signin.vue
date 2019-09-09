<template>
  <v-app>
    <v-content class="signin--backdrop">
      <v-container fluid>
        <v-row>
          <v-col cols="12">
            <nuxt-child />
          </v-col>
        </v-row>
      </v-container>
    </v-content>
  </v-app>
</template>

<script>
export default {}
</script>

<style lang="scss">
.signin--backdrop {
  background: rgb(46, 213, 115);
  background: -moz-linear-gradient(
    45deg,
    rgba(46, 213, 115, 1) 0%,
    rgba(30, 150, 81, 1) 55%
  );
  background: -webkit-linear-gradient(
    45deg,
    rgba(46, 213, 115, 1) 0%,
    rgba(30, 150, 81, 1) 55%
  );
  background: linear-gradient(
    45deg,
    rgba(46, 213, 115, 1) 0%,
    rgba(30, 150, 81, 1) 55%
  );
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr="#2ed573",endColorstr="#1e9651",GradientType=1);
}
</style>
