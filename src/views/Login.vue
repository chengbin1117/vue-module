<template>
  <div class="login">
    <!-- <h1>集结号后台管理系统</h1> -->
    <div class="container">
      <el-input v-model="userName" placeholder="请输入用户名"></el-input>
      <el-input v-model="passWord" placeholder="请输入密码" type="password"></el-input>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: "login",
  components: {},
  data() {
    return {
      userName: "",
      passWord: ""
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="stylus">
.login
  background #fff
  .container
    width 300px
    height 300px
    margin 0 auto
</style>
