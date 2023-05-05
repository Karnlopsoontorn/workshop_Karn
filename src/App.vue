<template>
  <div id="app">
    <v-bottom-navigation :elevation="24">
    <v-btn value to = "/Profile">
    <v-icon>mdi-face-man-profile</v-icon>
    Profile
  </v-btn>

  <v-btn value to = "/Contact">
    <v-icon>mdi-account-box</v-icon>

    Contact
  </v-btn>

  <v-btn value to ="/Project">
    <v-icon>mdi-presentation</v-icon>

    Project
  </v-btn>

  <v-btn value to = "/">
    <v-icon>mdi-home</v-icon>

    HOME
  </v-btn>
  
</v-bottom-navigation>
    <router-view />
  </div>
</template>

<script>
export default {
   name: 'App',

   data: () => ({
      //
   })
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.router-link-exact-active {
  color: blue;
}
</style>