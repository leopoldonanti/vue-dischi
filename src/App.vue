<template>
  <div id="app">

    <HeaderMine/>
    <MainMine/>

  </div>

</template>

<script>

import HeaderMine from './components/HeaderMine.vue';
import MainMine from './components/MainMine.vue';
import axios from 'axios';

export default {
  name: 'App',
  data(){
    return{
      axios
    }
  },
  created(){
   axios.get('https://flynn.boolean.careers/exercises/api/array/music')
    .then ( res => {
      console.log(res.data);
    })
    .catch(err =>{
      console.log(err);
    });
  },
  components: {
    HeaderMine,
    MainMine,
  }
}
</script>

<style lang="scss">
  body{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }
</style>
