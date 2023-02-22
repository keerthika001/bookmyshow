<template lang="pug">
.app-header
    nav
        .primary
            a Home
            a Movies
            a Events
        .seondary
            i(class="pi pi-user")
</template>

<script>
export default {
  setup() {
    
  },
}
</script>

<style lang="sass" scoped>
@import './src/styles/book-ticket.sass'
.app-header
    color: $white
    nav
        +flex-fill
        .primary
            a
                color: $white
                padding: 0 $s2

</style>


