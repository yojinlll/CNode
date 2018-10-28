<template>
  <div class="header">
    <img src="../assets/cnodejs_light.svg">
    <ul>
      <li><a href="#">首页</a></li>
      <li><a href="#">新手入门</a></li>
      <li><a href="#">API</a></li>
      <li><a href="#">关于</a></li>
      <li><a href="#">注册</a></li>
      <li><a href="#">登录</a></li>
    </ul>
  </div>
</template>

<script>
  export default {
    name: 'CNHeader',
    data(){
      return { msg:'fuck vue'}
    }
  }
</script>

<style scoped>
  .header{
    background-color: #444;
    height: 50px;
  }
  img{
    max-width: 120px;
    margin-left: 67px;
    margin-top: 8px;
  }
  ul{
    list-style: none;
    float: right;
    margin: 4px;
  }
  li{
    display: inline-block;
    padding: 10px 15px;
  }
  a{
    text-decoration: none;
    color: #ccc;
    font-size: 14px;
  }

</style>
