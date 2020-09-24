<template>
  
  <div class="frame-screen-list"  v-if="type==='list'">
    <div class="swiper">swiper</div>
    <div class="item">item</div>
    <div class="item">item</div>
    <div class="item">item</div>
    <div class="item">item</div>
    <div class="item">item</div>
    <div class="item">item</div>
  </div>
  
  <div class="frame-screen-detail" v-else>

  </div>
  
</template>

<script>
  export default{
    props:{
      type:{
        type:String,
      }
    }
  }
</script>

<style scoped>
</style>
