<template>
  <div>
    <TitleComp />
    <heroComp />
  </div>
</template>

<script>
import TitleComp from './components/TitleComp.vue'
import HeroComp from './components/HeroComp.vue'

export default {
  name: 'App',
  components: {
    TitleComp,
    HeroComp
  }
}
</script>

<style lang="scss">

</style>
