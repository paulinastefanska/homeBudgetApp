<template>
  <div class="flex items-center justify-center">
    <router-link to="/">
      <Button class="mr-2">
        Home
      </Button>
    </router-link>

    <router-link to="/budget">
      <Button>
        Budget
      </Button>
    </router-link>
  </div>
</template>

<script>
import Button from '../components/Button'

export default {
  name: 'Navigation',

  components: {
    Button
  }
}
</script>
