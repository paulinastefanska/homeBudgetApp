<template>
  <div class="flex flex-col items-center justify-center">
    <div
      class="h-48 w-48 flex items-center justify-center bg-black rounded-full mt-12"
    >
      <span class="text-center text-4xl text-white uppercase">
        {{ hello }}
      </span>
    </div>
    <p class="w-1/3 text-black mt-12">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',

  data() {
    return {
      hello: 'hello world'
    }
  }
}
</script>

<style scoped>
</style>
