<template>
  <div id="app">
    <Navbar/>
    <router-view/>
  </div>
</template>

<script>
import Navbar from '@/components/GlobalComponents/Navbar.vue'
export default {
  components: {
    Navbar
  }
}
</script>
<style lang="scss">

@import '@/styles/colors.scss';
@import '@/styles/typography.scss';

#app {
  font-family: $system-font-family;
  color: #2c3e50;
}

</style>
