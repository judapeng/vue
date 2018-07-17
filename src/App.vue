<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
import Vue from "vue";
import App from './App' 
export default {
    name:'app',
    data(){
      return{
        message:'我是vue'



      }



    }




}

</script>


<style lang="scss">
  @import "./lib/style/usage/core/reset.scss";
  body{
    font-size: 100px;
    width: 100%;
  }

</style>
