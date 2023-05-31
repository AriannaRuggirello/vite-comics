<script>
import AppHeader from './components/AppHeader.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  components: {
    AppHeader,

    AppFooter
  }
}

</script>

<template>
  <div class="container">
    <AppHeader />
  </div>
  <AppFooter />
</template>

<style lang="scss" >
@use './styles/partials/variables.scss' as *;
@use './styles/partials/mixin.scss' as *;
@use './styles/general.scss' as *;
</style>
