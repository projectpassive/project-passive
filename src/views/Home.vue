<template>
  <div class="home-page">
    <div class="hero">
      <div class="navbar max">
        <img class="logo" src="@/assets/logo-wide-light.svg">
      </div>
      <div class="splash">
        <h1>Start earning passive income today.</h1>
      </div>
    </div>

    <div class="flex-box">
      <div class="left-box">
        <div class="left-text">
          <!-- <div class="bar"></div> -->
          <h2>What We Do</h2><br>
          <p>Project Passive was created to provide its clients with a simple stream of passive income.
          We employ a team that automates the entire dropshipping flow between Amazon, Walmart, and Shopify - leaving you with as minimal work as possible.
          <br><br>We are here to help you with every step of the journey. We take care of everything from LLC creation
          to getting through the rigorous application process with Walmart and Amazon.</p>
        </div>
      </div>  
      <div class="right-image">
      </div>
    </div>


    <div class="section-two">
      <h2>Dropshipping Partners</h2>
      <div class="logo-row">
        <img class="drop-logo" src="@/assets/amazon.svg" alt="Amazon Logo">
        <img class="drop-logo" src="@/assets/shopify.svg" alt="Shopify Logo">
        <img class="drop-logo" src="@/assets/walmart.svg" alt="Walmart Logo">
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


