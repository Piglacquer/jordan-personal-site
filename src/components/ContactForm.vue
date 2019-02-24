<template>
  <div class='contact-form'>
    <div class='name-email'>
      <input type="text" placeholder="name" v-model='name'>
      <input type="text" placeholder="email" v-model='email'>
    </div>
    <textarea placeholder="message" v-model='message'/>
    <div class='submit-button'>
      Submit
    </div>
  </div>
</template>

<script>
export default {
  name:'contactForm',
  data () {
    return {
      name: '',
      email: '',
      message: ''
    }
  }
}
</script>

<style scoped>
  .contact-form {
    display: flex;
    flex-flow: column nowrap;
    align-items: center;
    justify-content: space-evenly;
    height: 66vh;
  }
  input {
    width: 33vw;
  }
  input, textarea {
    background-color: black;
    color: white;
    font-size: 2em;
    border-width: 0 0 2px 2px;
  }
  textarea {
    width: 66vw;
    height: 33vh;
  }
  .submit-button {
    width: 33vw;
    height: 10vh;
    background-color: white;
    color: black;
  }
</style>
