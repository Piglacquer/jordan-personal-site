<template>
  <div id='nav'>
    <div class='main'>
      <router-link class='link' to='/'>Home</router-link>
    </div>
    <div class='links'>
      <router-link class='link' to='/work'>Work</router-link>
      <router-link class='link' to='/about'>About</router-link>
      <router-link class='link' to='/contact'>Contact</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name:'navBar'
}
</script>

<style scoped>
  #nav {
    display: flex;
    flex-flow: row nowrap;
    background-color: transparent;
    justify-content: space-between;
    align-items: center;
    height: 10vh;
  }
  .main {
    padding-left: 20px;
  }
  .links {
    width: 25vw;
    display: flex;
    flex-flow: row nowrap;
    align-items: center;
    justify-content: space-between;
    padding-right: 20px;
  }
  .link {
    text-decoration: none;
    color: white;
  }
  .link:visted {
    color: white;
  }
</style>
