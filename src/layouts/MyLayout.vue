<template style="background-color: black">
  <q-layout view="lHh Lpr lFf">
    <q-header elevated class="bg">
    <q-toolbar>
        <q-toolbar-title class="text-center">
          <q-avatar>
            <img src="https://www.freeiconspng.com/uploads/movie-icon-27.png">
          </q-avatar>
          MoviesApp
        </q-toolbar-title>
      </q-toolbar>
    </q-header>
    <q-page-container style="background-color: #FDD935">
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
export default {
  name: 'MyLayout',

  data () {
    return {
    }
  }
}
</script>
<style scoped>
  .bg {
    background-color: #000000;
    color: #feffff;
    font-family: Impact;
  }
</style>
