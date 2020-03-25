<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'Bujo',
  data () {
    return {
      msg: 'Welcome to Bujo'
    }
  }
}
</script>

<style>
</style>
