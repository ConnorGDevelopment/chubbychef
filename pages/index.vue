<template>
  <v-row class="align-center">
    <v-col cols="2" class="pa-0 text-center">
      <v-btn icon height="10em" width="10em">
        <v-icon color="white" size="8em">
          mdi-gamepad-variant
        </v-icon>
      </v-btn>
    </v-col>
    <v-col cols="8" style="height: 100%" class="pa-0">
      <v-card style="height: 80%; margin-top: 10%; border: solid 4px white" tile>
        <v-card-title style="height: 100%">
          <v-img :src="require('~/assets/img/logo.jpg')" height="100%" width="100%" />
        </v-card-title>
      </v-card>
      <v-card class="transparent" style="height: 10%">
        <v-card-title class="text-h2 justify-center">
          Chubby Chef Gaming
        </v-card-title>
      </v-card>
    </v-col>
    <v-col cols="2" class="pa-0 text-center">
      <v-btn icon height="10em" width="10em">
        <v-icon color="white" size="8em">
          mdi-chef-hat
        </v-icon>
      </v-btn>
    </v-col>
  </v-row>
</template>
