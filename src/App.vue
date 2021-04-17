<template>
  <div id="app" :class="theme">
    <!-- <div class="topline" /> -->
    <!-- <div class="navbar max">
      <img class="logo" src="@/assets/logo-wide-blue.svg">
    </div> -->
    <router-view/>
    <Footer/>
  </div>
</template>

<script>
import Footer from '@/components/Footer'

export default {
  components: {
    Footer,
  },

}

</script>

<style src="@/css/main.scss" lang="scss" />
