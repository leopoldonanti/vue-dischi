<template>
  <main>
    <div class="container">

       <div 
            class="card">
         
        <h1>IMG</h1>
        <h1>ALBUM</h1>
        <h4>BAND</h4>
        <h5>ANNO</h5>
         
       </div>
       
    </div>
  </main>
</template>

<script>
export default {
  name: 'MainMine',

}
</script>

<style lang="scss" scoped>

  main{
  width: 100%;
  height: 713px;
  background-color: rgb(30, 45, 59);
  display: flex;
  align-items: center;
  justify-content: center;

    .container{
    width: 900px;
    background-color: crimson;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;

      .card{
      width: 200px;
      background-color: chartreuse;
      display: flex;
      flex-direction: column;
      align-items: center;
      margin: 10px 10px 10px 10px; 
      background-color: rgb(46, 58, 70);
      }
    } 
  }
  


</style>