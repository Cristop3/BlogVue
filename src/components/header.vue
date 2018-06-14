<template>
    <div id="myHeader">
        <div class="row">
            <div class="col-md-12 col-xs-12">
                <div class="row">
                    <div class="col-md-12 col-xs-12">
                        <img class="headImg" src="../assets/img/head.jpg" />
                    </div>
                    <div class="col-md-12 col-xs-12">
                        <h3>Caristop3</h3>
                    </div>
                    <div class="col-md-12 col-xs-12">
                        <p>Life is like a box of chocolate,you never know what you are going to get</p>
                    </div>
                </div>
            </div>
        </div>
        <div class='row'>
            <div class='col-md-12 col-xs-12'>
                <my-navbar></my-navbar>
            </div>
        </div>
    </div>
</template>

<script>
import myNavbar from "./navbars.vue"
export default {
    name:'myHeader',
    components:{
        'my-navbar': myNavbar
    }
}
</script>

<style scoped>
    @import '../assets/header.css';
</style>


