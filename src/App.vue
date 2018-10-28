<template>
  <div id="app">
  <c-header></c-header>
  </div>
</template>

<script>
import Header from './components/Header'

export default {
  name: 'App',
  components: {
    'c-header':Header,
  },
}
</script>

<style>
#app {

}
</style>
