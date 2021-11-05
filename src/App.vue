<template>
  <div id="app" class="container">
    <div class="row py-4">
      <biodata-satu/>
      <biodata-dua/>
    </div>
  </div>
</template>

<script>
  import BiodataSatu from './components/BiodataSatu.vue'
  import BiodataDua from './components/BiodataDua.vue'

export default {
  name: 'app',
  components: {
    BiodataSatu,
    BiodataDua
  }
}
</script>
