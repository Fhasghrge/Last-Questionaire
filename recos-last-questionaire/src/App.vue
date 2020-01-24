<template>
  <div id="app">
    <login></login>
  </div>
</template>

<script>
import login from './components/main'

export default {
  name: 'app',
  components: {
    login
  }
}
</script>

<style>
@import url('./assets/css/css.css');
@import url('./assets/css/reset.css');
</style>
