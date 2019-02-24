<template>
  <div class='contact'>
    <ContactForm />
  </div>
</template>

<script>
import ContactForm from '../components/ContactForm.vue'

export default {
  name: 'contact',
  components: {
    ContactForm
  }
}
</script>

<style scoped>
  .contact {
    margin-top: 15vh;
  }
</style>
