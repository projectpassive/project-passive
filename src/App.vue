<template>
  <div id="app" :class="theme">
    <div class="topline" />
    <div class="navbar max">
      <img class="logo-light" src="@/assets/logo-wide-light.svg">
      <!-- <div class="nav-links">
        <theme-switcher :theme="theme" class="theme-switcher" @themeChanged="updateTheme" />
      </div> -->
    </div>
    <router-view/>
    <Footer/>
  </div>
</template>

<script>
// import ThemeSwitcher from '@/components/ThemeSwitcher'
import Footer from '@/components/Footer'

export default {
  components: {
    // ThemeSwitcher,
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
