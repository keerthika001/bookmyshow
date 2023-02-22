<template lang="pug">
.home
  app-header
</template>


<script>
import AppHeader from '../src/components/AppHeader'
export default {
  components: {
    AppHeader
  },
  setup() {
    
  },
}
</script>

<style lang="sass" scoped>
@import '../src/styles/book-ticket.sass'
.home
  background-color: $primary
  height: 100vh
  padding: $s2
  h2
    color: $white
</style>
<style lang="sass">
@import '../src/styles/book-ticket.sass'
</style>

