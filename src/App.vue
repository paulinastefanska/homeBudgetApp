<template>
  <div
    id="app"
    class="container mx-auto py-4"
  >
    <Navigation />
    <router-view/>
  </div>
</template>

<script>
import Navigation from './components/Navigation'

export default {
  name: 'App',

  components: {
    Navigation
  }
}
</script>
