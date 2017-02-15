<template>
  <div class = "container" id="app">
    <my-navbar></my-navbar>
    <router-view></router-view>

  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'

export default {
    components: {
        'my-navbar': Navbar
    }
}
</script>

<style lang="scss">

</style>
