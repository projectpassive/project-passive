<template>
  <div class="home-page">
    <div class="hero">
      <h1>Start earning passive income today.</h1>
    </div>
    <div class="section-one">
      <div class="wrapper">
      <h2>What We Do</h2>
      <p>Project Passive was created to provide its clients with a simple stream of passive income.
        We employ a team that automates the entire dropshipping flow between Amazon, Walmart, and Shopify - leaving you with as minimal work as possible.
        <br><br>We are here to help you with every step of the journey. We take care of everything from LLC creation
        to getting through the rigorous application process with Walmart and Amazon.</p>
      </div>
    </div>
    <div class="section-two">
      <h2>Dropshipping Partners</h2>
      <div class="logo-row">
        <img class="drop-logo" src="@/assets/amazon_logo.svg" alt="Amazon Logo">
        <img class="drop-logo" src="@/assets/shopify-logo.svg" alt="Shopify Logo">
        <img class="drop-logo" src="@/assets/walmart_logo.svg" alt="Walmart Logo">
      </div>
    </div>
    <Contact/>
  </div>
</template>

<script>
import Contact from '@/components/Contact.vue'

export default {
  name: 'Home',
  components: {
    Contact,
  }
}
</script>


