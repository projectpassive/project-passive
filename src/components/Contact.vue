<template>
<div class="contact max">
    <h2>Contact</h2>
    <form name="Contact" method="POST" data-netlify="true" data-netlify-honeypot="bot-field">
      <input type="hidden" name="form-name" value="Contact" />
        <input type="text" name="name" placeholder="Name"/>   
        <input type="email" name="email" placeholder="Email"/>
        <textarea name="message" placeholder="Message"></textarea>
        <div class="form-btn"><button type="submit">SUBMIT</button></div>
    </form>
</div>
</template>

<script>
export default {
  name: 'Contact',
}
</script>