<template>
  <header>
    <img src="../assets/img/spotify-logo.png" alt="">
  </header>
</template>

<script>
export default {
  name: 'HeaderMain',
}
</script>

<style lang="scss" scoped>

  header{
    width: 100%;
    height: 60px;
    background-color: rgb(46, 58, 70);
    display: flex;
    align-items: center;
    
      img{
        height: 50px;
        margin-left: 30px;
      }
  }

</style>