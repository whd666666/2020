<template>
  <div class="no-page">
   <img src="../assets/img/16.jpg" alt="">
       <router-link to="/home">回到首页</router-link>
  </div>
</template>

<script>
  export default {
    name:'no-page',
    props:{},
    data(){
      return {
        
      }
    },
    components:{},
    mounted(){},
    updated(){},
    methods:{}
  }
</script>

<style>
  .no-page{
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
  }
  img{
	  width: 100%;
	  height: 100%;
  }
</style>
