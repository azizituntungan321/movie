<template>
  <div class="q-pa-md">
    <q-layout view="lHh lpr lFf" container style="height: 1000px">
      <q-page-container>
        <q-page class="row" style="justify-content: center">
            <q-card class="card-movie" v-for="n in 15" :key="n" style="margin: 20px; align-items: center">
              <img src="https://cdn.quasar.dev/img/mountains.jpg">
              <q-card-section>
                <div class="text-h6">Our Changing Planet</div>
                <div class="text-subtitle2">by John Doe</div>
              </q-card-section>
            </q-card>
        </q-page>
      </q-page-container>
    </q-layout>
  </div>
</template>

<script>
export default {
  name: 'P_Home'
}
</script>

<style scoped>
  .bg {
    background-color: #3aafa9;
  }
  .card-movie {
    width: 100%;
    height: auto;
    max-width: 250px;
    min-height: 100px;
  }
</style>
