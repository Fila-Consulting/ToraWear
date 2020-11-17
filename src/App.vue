<template>
  <div id="app">

      <app-menu></app-menu>
    <router-view/>
  </div>
</template>

<script>
import menu from "./components/menu";
export default {
  name: 'App',
  components: {
    appMenu: menu,
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
}

</style>
