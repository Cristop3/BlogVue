<template>
  <div id="app" class="container">
    <!-- 头部 -->
    <my-header></my-header>
  </div>
</template>

<script>
import myHeader from './components/header.vue'
export default {
  name: 'App',
  components:{
    'my-header':myHeader
  }
}
</script>

<style scoped>
@import './assets/index.css'
</style>
