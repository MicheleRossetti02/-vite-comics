<script >

// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import SiteHeader from './components/SiteHeader.vue'
import FirstBlock from './components/FirstBlock.vue'
import SecondBlock from './components/SecondBlock.vue'
import ThirdBlock from './components/ThirdBlock.vue'
import SiteFooter from './components/Footer.vue'
export default {
  name: 'App',
  components: {
    SiteHeader,
    FirstBlock,
    SecondBlock,
    ThirdBlock,
    SiteFooter,
  }
}
</script>

<template>

  <site-header></site-header>

  <first-block></first-block>

  <second-block></second-block>

  <third-block></third-block>

  <site-footer></site-footer>




</template>

<style scoped>

</style>
