<template>
  <div class="entrance" @click="$router.push({name: 'entrance'})">
    <img src="../../assets/img/entrance.png"/>
  </div>
</template>

<script>
  export default {
    name: 'entrance'
  }
</script>

<style scoped>
  .entrance {
    position: fixed;
    z-index: 990;
    bottom: 65px;
    right: 3%;
    width: 75px;
    height: auto;
  }

  .entrance img {
    display: block;
    width: 100%;
    height: auto;
  }
</style>
