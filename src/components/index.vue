<template lang="pug">
.container
  h1.hello
    | {{greeting}}
</template>

<style lang="sass" scoped>
.hello
  color: #789
</style>

<script>
export default {
  data() {
    return {
      greeting: 'Hello!'
    }
  }
}
</script>
