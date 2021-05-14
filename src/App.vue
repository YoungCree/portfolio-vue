<template>
  <div id="app">
    <md-toolbar class="md-transparent" md-elevation="0">
      <h3 class="md-title" style="flex: 1">Corey's Portfolio</h3>
      <router-link to="/"><md-button class="nav-btn">Home</md-button></router-link>
      <router-link to="/about"><md-button class="nav-btn">About</md-button></router-link>
    </md-toolbar>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: Roboto;
}

.nav-btn a {
  color: white !important;
  text-decoration: none !important;
}

</style>
