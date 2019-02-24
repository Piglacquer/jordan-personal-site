<template>
  <div class='work'>
    <div class='work-block'>
      <div class='work-stacked'>
        <img src='' alt=''>
        <img src='' alt=''>
      </div>
      <img src='' alt=''>
    </div>
  </div>
</template>

<script>

export default {
  name: 'work',
  components: {}
}
</script>

<style scoped>
  .work {
    
  }
  .work-block {
    display: flex;
    flex-flow: row nowrap;
  }
  .work-stacked {
    display: flex;
    flex-flow: column nowrap;
  }
</style>
