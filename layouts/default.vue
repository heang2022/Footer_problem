<template>
  <div>
    <AppHeader/>
    <BlackWrapUpFooter/>
    <AppFooter/>
    <nuxt/>
  </div>
</template>

<script>
  import AppHeader from '../components/AppHeader'
  import BlackWrapUpFooter from '../components/BlackWrapUpFooter'
  import AppFooter from '../components/AppFooter'

  export default {
    components: {
      AppHeader,
      BlackWrapUpFooter,
      AppFooter
    }
  }
</script>
