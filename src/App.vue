<template>
<!--  <div id="login">-->
<!--    用户名:<input type="text"  id="username" name="username"><br>-->
<!--    密&nbsp;&nbsp;&nbsp;&nbsp;码:<input type="password" name="password"><br>-->
<!--    <input type="button" name="login" alt="登录">-->
<!--  </div>-->
  <div id="app">
    <router-view />
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
/*#login {*/
/*  font-family: 'Avenir', Helvetica, Arial, sans-serif;*/
/*  -webkit-font-smoothing: antialiased;*/
/*  -moz-osx-font-smoothing: grayscale;*/
/*  text-align: center;*/
/*  color: #2c3e50;*/
/*  margin-top: 60px;*/
/*}*/
</style>
