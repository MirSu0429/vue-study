<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
  </div>
 <!-- <div class="test">
    <h1>{{msg}}</h1>
  </div>-->
</template>

<script>
export default {
  name: 'app'
 /* data () {
    return {
      msg: '测试'
    }
  }*/
}

</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
