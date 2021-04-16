<template>
  <div id="app" :class="theme">
    <div class="topline" />
    <div class="navbar max">
      <img class="logo-light" src="@/assets/logo-wide-blue.svg">
    </div>
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
  mounted() {
    this.theme = localStorage.getItem('theme') || 'theme-light'
  },
  data() {
    return {
      theme: '',
    }
  },
  methods: {
    toggle() {
      this.isOpen = !this.isOpen
    },
    updateTheme(theme) {
      this.theme = theme
    }
  }
}
</script>

<style src="@/css/main.scss" lang="scss" />
