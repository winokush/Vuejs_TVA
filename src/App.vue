<template>
  <div id="app" class="container">
    <div class="row justify-content-center text-center">
      <div class="col-6">
          <img src="./assets/tva.png" alt="Tva logo">
          <Tva msg="VTA calculation for winokush"/>
      </div>
    </div>
  </div>
</template>

<script>
import Tva from './components/Tva'

export default {
  name: 'App',
  components: {
    Tva
  }
}
</script>

<style>
    body {
        padding-top: 2rem;
    }
</style>
