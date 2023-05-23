<template>
  <div id="app">
    <FirstPage />
  </div>
</template>

<script>
import FirstPage from './components/FirstPage.vue'

export default {
  name: 'App',
  components: {
    FirstPage,
  },
}
</script>

<style>
body {
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100vh;
}
</style>
