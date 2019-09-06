<template>
  <div id="app">
    <div class="header">
      2019-2020学年校历
    </div>
    <calendar></calendar>
    <router-link to="/" class="copyright">JY项目组</router-link> |
    <router-link to="/about" class="copyright">掌上建院</router-link>
  </div>
</template>

<style>
  body{
    background-color: #ffffff;
  }
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 30px;
}
.header{
  width: 100%;
  height: 40px;
  line-height: 40px;
  margin: 0 auto 25px auto;
  text-align: center;
  font-family: 阿里汉仪智能黑体 ;
  font-size: 25px;
  color: #42b983;
}
#nav{
  color: #42b983;
}
  .copyright{
    text-decoration: none;
    color: #42b983;
  }
  div .el-calendar-day{
    height: 50px;
  }
</style>
<script>
  import Calendar from "./components/calendar";
  export default {
    components: {Calendar}
  }
</script>
