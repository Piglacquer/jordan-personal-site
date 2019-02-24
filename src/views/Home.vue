<template>
  <div class="home">
    <div class="block-1">
      <div class="sticky">Here's some work</div>
    </div>
    <div class="block-2">
    </div>
    <div class="block-3">
      <div class="sticky">MOAR WORKS</div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'home',
  components: {}
}
</script>

<style scoped>
  .home {
    height: 100vh;
  }
  /* .img {
    position: absolute;
    background-size: cover;
    height: 100%;
    width: 100%;
  }
  .one {
    background-image: url('../assets/1.jpg');
    z-index: -1;
  }
  .two {
     background-image: url('../assets/2.jpg');
    z-index: -2;
  } */
  @import url('https://fonts.googleapis.com/css?family=Abril+Fatface');

.sticky
{
  position: sticky;
  position: -webkit-sticky;
  top: 30px;
  font: 90px 'Abril Fatface', sans-serif;
  color: #fff;
  text-align: center;
}
.block-1, .block-3
{
  height: 900px;
  padding: 70px 20px;
  background-size: cover;
  background-image: url('http://www.tipue.com/img/elvis.jpg');
  box-sizing: border-box;
  background-position: center;
}
.block-2
{
  background: url('http://www.tipue.com/img/bomp.jpg') no-repeat fixed;
  background-size: cover;
  height: 900px;
  background-position: center;
}
.block-3
{
  background-image: url('http://www.tipue.com/img/look.jpg');
}

</style>
