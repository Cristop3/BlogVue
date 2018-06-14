<template>
  <div id="myNavbar">
    <ul class="myUl nav">
      <li v-for="(item,index) in nav" class="navItem" :class="{'activeCheck':index == checkindex}" @click="toggle(index)">{{item}}</li>
    </ul>
  </div>
</template>

<script>
  export default {
    name: 'myNavbar',
    data:function(){
        return {
            nav:[
                '首页','归档','关于','联系'
            ],
            checkindex:0
        }
    },
    methods:{
        toggle:function(index){
            this.checkindex = index
        }
    }
  }

</script>

<style scoped>
    @import '../assets/navbar.css';
</style>
